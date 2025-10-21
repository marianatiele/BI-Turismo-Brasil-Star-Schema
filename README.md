# Análise de Turismo Internacional no Brasil - Chegadas

Este projeto apresenta um Dashboard interativo desenvolvido para analisar e visualizar o fluxo de turistas internacionais no Brasil, detalhando as origens (países e continentes) e os destinos (estados).

O objetivo é identificar os principais *drivers* de chegadas para informar estratégias de marketing e alocação de recursos.



## Tecnologias e Metodologia

* **Ferramenta Principal:** Power BI
* **Modelagem de Dados:** Utilização de um **Star Schema** 
    * **Tabela Fato:** `fato_chegadas` (métrica de chegadas).
    * **Tabelas Dimensão:** `dim_pais`, `dim_data`, `dim_continente`, `dim_destino`, `dim_via`.
* **Limpeza e Transformação:** Uso do Power Query para tratar dados de tempo e criar hierarquias.
* **Design & Visualização:** Aplicação de princípios de *Data Storytelling*, como a hierarquia visual.



## Principais Descobertas e Insights

A análise rápida do painel final (abaixo) revela os seguintes insights críticos:

1.  **Origem Dominante (Foco Geográfico):** A **América do Sul** é o principal continente emissor de turistas, respondendo por mais da metade de todas as chegadas (57.93%).
2.  **Top Driver:** A **Argentina** é, de longe, o principal país emissor de turistas no período analisado, superando significativamente o segundo colocado (Estados Unidos).
3.  **Concentração de Destino:** O turismo é altamente concentrado, com **São Paulo** e **Rio de Janeiro** liderando o ranking de estados mais visitados. Isso sugere oportunidades para desenvolver o turismo em outras regiões.
4.  **Atenção ao Design:** Utilização da cor primária (azul escuro) para destacar intencionalmente o **driver principal** em cada gráfico (Argentina, São Paulo, América do Sul), guiando o olhar do usuário e priorizando a informação.



## Visualização Final do Dashboard

<img width="875" height="491" alt="image" src="https://github.com/user-attachments/assets/28dcb1a4-fb18-4ec9-a838-cdd7af7accdb" />



##  Fonte de Dados

Os dados utilizados neste projeto são públicos e foram obtidos através do portal de dados abertos do governo brasileiro.

* **Dataset:** Estimativas de Chegadas de Turistas Internacionais ao Brasil
* **Link:** [https://dados.gov.br/dados/conjuntos-dados/estimativas-de-chegadas-de-turistas-internacionais-ao-brasil](https://dados.gov.br/dados/conjuntos-dados/estimativas-de-chegadas-de-turistas-internacionais-ao-brasil)


