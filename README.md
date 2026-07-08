# Cookie Crooki — Site

Site de página única (vitrine + cardápio) da Cookie Crooki, com pedidos via WhatsApp.

## Estrutura
- `index.html` — o site completo (HTML/CSS/JS em um arquivo só)
- `img/` — fotos dos cookies e da fundadora
- `video/` — vídeo do hero
- `.nojekyll` — garante que o GitHub Pages sirva todos os arquivos

## Publicar (GitHub Pages)
1. Suba estes arquivos para um repositório público.
2. Em **Settings → Pages**, selecione a branch `main` e a pasta `/ (root)`.
3. O site fica no ar em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

## Editar depois
- WhatsApp e Instagram: topo do `index.html` (`window.WHATSAPP` / `window.INSTAGRAM`).
- Sabores e preços: array `flavors` no `<script>`.
