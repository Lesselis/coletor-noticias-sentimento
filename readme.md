## Introdução
Este documento apresenta casos de uso para o desenvolvimento de um sistema de coleta de notícias e análise de sentimento. O objetivo do projeto é criar uma aplicação web que permita aos usuários coletar notícias de fontes específicas, realizar análise de sentimento no conteúdo coletado e visualizar os resultados em gráficos e tabelas.

## Ferramentas Utilizadas
- **Interfaces Gráficas (GUI)**: Flask
- **Gráficos**: Matplotlib
- **Processamento de Dados**: Pandas
- **Web Scraping**: Newspaper3K
- **Análise de Sentimento**: TextBlob

## Casos de Uso

### Caso de Uso 1: Coleta de Notícias
**Descrição**: Permitir que o usuário colete notícias de fontes específicas.
- **Ator**: Usuário
- **Pré-condições**: O usuário deve fornecer a URL da fonte de notícias.
- **Fluxo Principal**:
  1. O usuário acessa a página de coleta de notícias.
  2. O usuário insere a URL da fonte de notícias.
  3. O sistema utiliza o Newspaper3K para coletar as notícias da fonte especificada.
  4. O sistema exibe as notícias coletadas ao usuário.
- **Pós-condições**: As notícias são exibidas ao usuário.

### Caso de Uso 2: Análise de Sentimento
**Descrição**: Realizar análise de sentimento no conteúdo das notícias coletadas.
- **Ator**: Usuário
- **Pré-condições**: O usuário deve ter coletado as notícias.
- **Fluxo Principal**:
  1. O usuário acessa a página de análise de sentimento.
  2. O sistema utiliza o TextBlob para realizar a análise de sentimento no conteúdo das notícias.
  3. O sistema exibe os resultados da análise de sentimento ao usuário.
- **Pós-condições**: Os resultados da análise de sentimento são exibidos ao usuário.

### Caso de Uso 3: Visualização dos Resultados
**Descrição**: Permitir que o usuário visualize os resultados da análise de sentimento em gráficos e tabelas.
- **Ator**: Usuário
- **Pré-condições**: O usuário deve ter realizado a análise de sentimento.
- **Fluxo Principal**:
  1. O usuário acessa a página de visualização dos resultados.
  2. O sistema utiliza o Matplotlib para gerar gráficos com os resultados da análise de sentimento.
  3. O sistema exibe os gráficos e tabelas ao usuário.
- **Pós-condições**: Os gráficos e tabelas são exibidos ao usuário.

## Considerações Finais
Este documento fornece uma visão geral dos requisitos e funcionalidades do sistema de coleta de notícias e análise de sentimento. Cada caso de uso detalha o fluxo principal de interação entre o usuário e o sistema.