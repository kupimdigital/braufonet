# BRAUFONET – Brazil UFO Network

Site da BRAUFONET (navegação espacial em 9 setores). Página única, sem build: basta publicar esta pasta como está.

## Estrutura
- `index.html` — o site completo (HTML, CSS e JavaScript no mesmo arquivo).
- `assets/` — fundo do universo (panorama e camadas do parallax), logo em camadas, nave, fonte Cinzel.
- `videos/` — intro (`intro.webm` principal e `intro_backup.mp4` de reserva).

## Publicar no GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → branch `main`, pasta `/ (root)`.

## Ajustes
Os valores visuais definitivos ficam no início do script do `index.html`, na linha `const PADRAO = { ... }`.
Para ajustar visualmente, use o `index_aux.html` do protótipo (fora deste repositório) e cole aqui a linha gerada em "Copiar ajustes".

Uma criação de [Kupim Digital](https://www.kupimdigital.com.br/).
