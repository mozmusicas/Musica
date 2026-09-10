# CYBER MUSIC **Plataforma editorial musical profissional — Cyber / Digital Media.** Website estático pronto para **GitHub Pages**. Conteúdo real e verificável. Zero publicidade. Zero placeholders fictícios. ## O que é CYBER MUSIC é uma plataforma editorial de música com: - Rankings reais (Billboard Hot 100 **United States** com data e fonte)
- Artigos editoriais originais baseados em factos verificáveis
- Artistas e músicas reais (internacionais + Moçambique + África)
- Secção dedicada à música de Moçambique (Marrabenta, Pandza, Hip-Hop, R&B, Jango)
- Player integrado com embeds oficiais do YouTube (modal + queue + prev/next)
- Pesquisa global em JSON (artistas, músicas, álbuns, notícias, charts) com links clicáveis
- Design cyber premium, responsivo e acessível ## Contagens (versão actual) | Recurso | Quantidade |
|---------|------------|
| Artistas | 30+ |
| Músicas | 30+ |
| Álbuns | 20+ |
| Artigos | 30+ |
| Previews oficiais (YouTube) | 25+ | ## Tecnologias - HTML5
- CSS3 (variáveis, glow, tickers, responsivo)
- JavaScript ES6+ (app.js, player.js, charts.js, news.js)
- JSON para dados actualizáveis
- SVG para ícones
- Thumbnails oficiais YouTube (`i.ytimg.com`) como capas quando há vídeo oficial
- Compatível com GitHub Pages (sem backend) ## Estrutura do projecto ```
cyber-music/
├── index.html
├── news.html
├── charts.html
├── artists.html
├── albums.html
├── music.html
├── videos.html
├── trending.html
├── global.html
├── mozambique.html
├── about.html
├── contact.html
├── privacy.html
├── terms.html
├── editorial-policy.html
├── copyright.html
├── cookies.html
├── css/
│ └── style.css
├── js/
│ ├── app.js
│ ├── player.js
│ ├── charts.js
│ └── news.js
├── data/
│ ├── artists.json
│ ├── songs.json
│ ├── albums.json
│ ├── news.json
│ └── charts.json
├── assets/
│ └── icons/
├── sitemap.xml
├── robots.txt
└── README.md
``` ## Como executar localmente 1. Extrair o ZIP ou clonar o repositório.
2. Servir a pasta como site estático (ex.: `npx serve.` ou Live Server).
3. Abrir via HTTP (não `file://`) para que o fetch dos JSON funcione. ## Publicar no GitHub Pages 1. Enviar o conteúdo da pasta `cyber-music/` para o repositório.
2. Settings → Pages → Source: branch main, pasta root.
3. Site em `https://<user>.github.io/<repo>/`. ## Player - Usa **apenas embeds oficiais YouTube**.
- **Não** hospeda ficheiros de áudio protegidos.
- Controlos: Play/Pause, Previous, Next, Mute, fechar modal.
- Fila (queue) com faixas oficiais.
- Barra inferior Now Playing.
- Sem preview oficial: **OFFICIAL PREVIEW UNAVAILABLE**. ## Pesquisa global Resultados clicáveis para:
- artists.html?artist=<id>
- music.html?song=<id>
- albums.html?album=<id>
- news.html?article=<id>
- charts.html#pos-N ## Imagens - Capas via thumbnails oficiais YouTube quando existe vídeo verificado.
- Ícones SVG locais.
- Sem fotos geradas por IA / rostos inventados.
- ALT descritivo. ## Charts - **Billboard Hot 100 (United States)** — não é global chart.
- Fonte, data do chart e data de actualização do site indicadas.
- Moçambique: notas verificáveis, sem rankings inventados. ## Fontes principais - Billboard Hot 100
- Canais oficiais YouTube
- Wikipedia (com referências)
- Music in Africa
- Lançamentos oficiais ## Política editorial Ver `editorial-policy.html`. Não inventar factos para cumprir quotas. ## Limitações - Sem áudio completo no repositório (copyright).
- Capas dependem de thumbnails YouTube públicos.
- Charts locais de Moçambique não fabricados. --- © 2026 CYBER MUSIC · Conteúdo editorial · Sem publicidade
