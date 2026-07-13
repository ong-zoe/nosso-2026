# Portal Zoé — site institucional

Site estático (HTML + JS + imagens). Não requer build.

## Estrutura
- `index.html` — a página
- `support.js` — runtime necessário (carregado por `index.html`)
- `assets/` — logo e fotos

## Publicar no Vercel (via GitHub)
1. Crie um repositório no GitHub e envie **todo o conteúdo desta pasta** para a raiz do repo.
2. No Vercel: **Add New → Project → Import** o repositório.
3. Em *Framework Preset* escolha **Other** (site estático).
   - Build Command: *(vazio)*
   - Output Directory: *(vazio / raiz)*
4. **Deploy**. A cada `git push`, o Vercel republica automaticamente.

## Observações
- O checkout **FundraiseUp** valida o domínio. Em `*.vercel.app` pode não abrir — aponte o domínio de vocês (ou configure o domínio no painel da FundraiseUp).
- O botão "Transparência total" leva para https://ongzoe.org/transparencia
