# Portal Institucional – AD Monte Alegre

Site estático (HTML, CSS e JavaScript puros), sem build e sem dependências.

## Estrutura

```
index.html              página principal
css/style.css           estilos
js/app.js               programação semanal, notícias e congregações
js/departamentos.js     janela de descrição dos departamentos
assets/img/             logos, fotos e imagens das notícias
.nojekyll               evita processamento do Jekyll no GitHub Pages
```

## Publicar no GitHub Pages

1. Crie um repositório no GitHub e envie todos os arquivos desta pasta para a raiz dele.
2. No repositório, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**, selecione a branch `main` e a pasta `/ (root)`, e clique em **Save**.
4. Em alguns minutos o site estará em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Como editar

- **Novo departamento:** copie um bloco `<div class="card dep">…</div>` em `index.html`, coloque a imagem em `assets/img/` e adicione o texto de descrição na lista `T` em `js/departamentos.js`, na mesma ordem dos cards.
- **Notícias, programação e congregações:** estão nas listas `N`, `D` e `A` em `js/app.js`.
- **Cores e fontes:** variáveis no início de `css/style.css`.
