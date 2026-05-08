Central Free Fire - Etapa 4

Use apenas esta pasta da Etapa 4. Não misture com Etapa 1, 2 ou 3.

O que mudou nesta etapa:
- Foi criado o arquivo js/config.js.
- Links das planilhas Google foram centralizados em window.CFF_CONFIG.sheets.
- Configuração do Firebase foi centralizada em window.CFF_CONFIG.firebase.
- O index.html agora carrega js/config.js antes dos outros scripts.

Como editar links de planilhas agora:
1. Abra js/config.js.
2. Procure a chave da planilha, por exemplo:
   - noticias
   - seaClassificacao
   - seaAbates
   - mercado
   - lives
3. Troque apenas o link ali.

Estrutura principal:
index.html
css/
  00-home-base.css
  01-navigation.css
  02-layout-torneios-tabelas.css
  03-day-vote.css
  04-mercado.css
  05-internacional-ffws-sea.css
js/
  config.js
  service-worker-register.js
  firebase-votes.js
  core-data.js
  stats-rankings.js
  search-history-compare.js
  day-vote.js
  filters-results.js
  team-profile.js
  navigation-search.js
  other-tournaments.js
  home-news-lives.js
  charts-market.js
  ffws-sea.js
