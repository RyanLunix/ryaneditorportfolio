# Portfólio do Ryan

Site de portfólio de editor de vídeos (HTML, CSS e JS puros, sem build).

## Estrutura
- `index.html`: o site inteiro
- `assets/ryan.jpg`: imagem do personagem

## Como editar
No começo do `<script>` de `index.html`, no bloco `EDITE AQUI`:
- `VIDEOS`: coloque o ID do YouTube (o que vem depois de `watch?v=`), o título e a categoria (`"long"` ou `"short"`).
- `FEEDBACKS`: coloque o caminho ou link de cada imagem de feedback (ex.: `"assets/feedback1.png"`).
- `T`: textos em inglês (`en`) e português (`pt`).

## Como publicar no GitHub Pages
1. Crie um repositório no GitHub e envie estes arquivos.
2. Vá em **Settings → Pages**.
3. Em **Source**, escolha **Deploy from a branch**, selecione `main` e a pasta `/ (root)`, e salve.
4. Em alguns minutos o site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.
