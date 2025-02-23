# Análise de Dados - Consumo de Álcool por País

Este projeto realiza uma análise exploratória de dados (EDA) sobre o consumo de álcool por país, utilizando R. O objetivo é compreender a distribuição, correlação e outras características dos dados.

## Packages Utilizados

* **dplyr**: Manipulação de dados, seleção e transformação de colunas.
* **tidyr**: Transformação de dados entre formatos largo e longo.
* **ggplot2**: Criação de gráficos estatísticos.
* **corrplot**: Visualização de matrizes de correlação.
* **plotly**: Criação de gráficos interativos.
* **reshape2**: Auxiliar na transformação de dados para gráficos de correlação.

## ETL (Extração - Transformação - Carga)

1.  **Fonte dos Dados:**
    * Dados referentes ao consumo de alcool em diversos países ao redor do mundo.

2.  **Metadados (Dicionário de Dados):**
    * `country`: Nome do país.
    * `beer_servings`: Número de porções de cerveja consumidas per capita.
    * `spirit_servings`: Número de porções de destilados consumidas per capita.
    * `wine_servings`: Número de porções de vinho consumidas per capita.
    * `total_litres_of_pure_alcohol`: Total de litros de álcool puro consumidos per capita.

