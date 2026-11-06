# radar-b3

Radar de notícias e relatórios de RI da B3.

- `dados.json`: gerado pelo Claude em tarefas agendadas (pré-abertura, de hora em hora no pregão e pós-fechamento). A página do Lovable apenas lê este arquivo.
- `INSTRUCOES.md`: regras e formato que o motor segue a cada rodada.
- `acompanhar.json`: tickers extras que o usuário quer que o motor pesquise (público: não colocar quantidades nem preços).
- `empresas.json`: catálogo de todas as ações da B3 (368 empresas, 521 tickers) por setor e segmento. A página usa para busca e navegação por categoria.

Não é recomendação de investimento.
