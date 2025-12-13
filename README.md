# COVID-19: Mortes e Vacinação — Análise Global

## Visão Geral

Este projeto apresenta uma análise exploratória e visual da pandemia de COVID-19 utilizando **Tableau** para visualização de dados e **SQL** para exploração inicial do dataset. O dashboard foca em números globais, impacto por continente, taxa de infecção por país e evolução temporal da pandemia.

## Objetivo

Fornecer uma visão clara e resumida sobre:

* Total de casos e mortes no mundo
* Distribuição de mortes por continente
* Percentual da população infectada por país
* Evolução mensal do percentual de população infectada

O projeto busca demonstrar habilidades de análise de dados, SQL e visualização em Tableau.

## Estrutura do Dashboard

O dashboard no Tableau é composto por **4 visualizações principais**:

### 1. Global Numbers (Tabela)

Tabela resumo com indicadores globais:

* **Total Cases:** soma do total de casos registrados
* **Total Deaths:** soma do total de mortes
* **Death Percentage:** percentual de mortes em relação aos casos

Serve como visão executiva rápida do impacto global da pandemia.

### 2. Total Deaths Per Continent (Gráfico de Barras Empilhadas)

* **Coluna:** Continente
* **Valor:** Soma do Total Death Count

Permite comparar o impacto da COVID-19 entre diferentes continentes.

### 3. Percent Population Infected Per Country (Mapa Preenchido)

Mapa mundial exibindo o percentual da população infectada em cada país, facilitando a identificação de regiões mais afetadas.

### 4. Percent Population Infected (Gráfico de Linha)

* **Eixo X:** Mês da data
* **Eixo Y:** Média do Percent Population Infected

Mostra a evolução temporal da taxa de infecção ao longo dos meses.

## Análise em SQL

Além do dashboard, o projeto inclui um script SQL para exploração dos dados:

* **Arquivo:** `COVID Portfolio Project - Data Exploration.sql`

Este script contém consultas para:

* Análise de casos e mortes ao longo do tempo
* Cálculo de percentuais de infecção e mortalidade
* Comparações entre países e continentes

O SQL foi utilizado como etapa inicial de entendimento e validação dos dados antes da visualização no Tableau.

## Tecnologias Utilizadas

* Tableau
* SQL (análise exploratória)
* Dataset público sobre COVID-19

## Como Usar

1. Abra o arquivo do dashboard no Tableau.
2. Explore as visualizações e interações disponíveis.
3. Consulte o script SQL para entender a exploração e preparação dos dados.

## O que Aprendi

* Exploração de grandes volumes de dados usando SQL.
* Criação de dashboards analíticos no Tableau.
* Transformação de análises técnicas em visualizações claras e informativas.

## Próximos Passos

* Adicionar filtros interativos no dashboard.
* Atualizar o dataset com dados mais recentes.
* Criar uma versão comparando períodos pré e pós vacinação.

---

*Este projeto faz parte do meu portfólio de análise de dados e visualização.*
