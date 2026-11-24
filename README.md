# Refúgio Wolski (nome provisório) · prévia do site dos chalés

Prévia feita pela RK Performance (https://rkperformance.com.br) para a Cleusa Wolski, de Prudentópolis/PR. Os chalés estão em construção: as imagens são ilustrativas.

- Página única em `index.html` (CSS e JS dentro dela), fontes em `fonts/`, mídia em `media/`.
- Abertura: `media/hero-16x9.mp4` em tela deitada e `media/hero-9x16.mp4` em tela em pé. No iPhone o filme entra como `<img>`; `?ios=1` força esse caminho para teste.
- Botão "Quero saber da abertura": preencher `WHATS` no fim do `index.html` (DDI + DDD + número, só dígitos). Vazio, o botão abre um aviso de prévia.
- `noindex` e `robots.txt` bloqueando buscadores enquanto for prévia.
- No ar: https://cleusa.rkperformance.com.br/ (GitHub Pages, branch `main`).
- Local: servidor `cleusa-chales-site` no `.claude/launch.json` da RK (porta 8832).
