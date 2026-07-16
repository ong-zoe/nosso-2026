# Fontes locais — Cooper Black

A landing page usa **Cooper Black** nos títulos e textos de destaque, com
**Coustard** (Google Fonts) como fallback enquanto a fonte local carrega.

Para a Cooper Black aparecer, coloque os dois arquivos `.otf` nesta pasta,
com exatamente estes nomes (referenciados pelo `@font-face` em `index.html`):

- `cooper-black.otf`         — regular
- `cooper-black-italic.otf`  — itálica

Enquanto os arquivos não estiverem aqui, a página usa Coustard/Georgia
automaticamente (`font-display: swap`), sem quebrar o layout.
