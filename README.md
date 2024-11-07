# Explorando Viajantes Globais

## Análise de Viajantes Globais

Este projeto realiza uma análise exploratória de dados de um conjunto de informações sobre viajantes globais, com o objetivo de entender os padrões de comportamento, custos e preferências em viagens internacionais. Os dados foram extraídos de um dataset do Kaggle: [Traveler Trip Data](https://www.kaggle.com/datasets/rkiattisak/traveler-trip-data). A análise foi realizada utilizando Python no Google Colab, com visualizações gráficas criadas usando Seaborn, Matplotlib, Plotly, e criação de dashboard no Power BI.

## Etapas do Projeto

### 1. Leitura e Preparação dos Dados

- O dataset foi carregado utilizando o **Pandas**.
- Foram realizadas limpezas e ajustes nos dados, como:
  - Remoção de valores nulos nas colunas essenciais.
  - Substituição de valores inconsistentes (ex.: "Flight" para "Plane").
  - Transformação de valores de custos de acomodação de strings para valores numéricos.
  - Conversão de idades para o formato inteiro.

### 2. Exploração Inicial

- Análise das dimensões do dataset (número de linhas e colunas).
- Renomeação das colunas para uma nomenclatura mais intuitiva em português.
- Análise estatística básica para entender a distribuição de variáveis.

### 3. Insights Principais

- **Distribuição de Idade**: A análise de idade dos viajantes revelou que a maioria dos viajantes possui idades entre 20 e 60 anos.
- **Gênero**: A distribuição de gênero foi explorada com gráficos de pizza, mostrando a proporção de viajantes masculinos e femininos, com uma proporção próxima entre os sexos.
- **Cidades mais visitadas**: As 10 cidades mais visitadas foram visualizadas utilizando um gráfico de barras, com destaque para as cidades mais populares entre os viajantes.
- **Acomodações e Transporte**: Foi feita uma análise do tipo de acomodação e transporte mais utilizados, com visualizações que destacam os tipos mais frequentes de transporte e acomodação.
- **Custos de Viagem**: A relação entre custo de transporte e acomodação foi explorada, além de um gráfico que apresenta o custo total de viagem por país.

### 4. Análises Avançadas

- **Duração da Viagem vs. Nacionalidade e Gênero**: Foi criada uma visualização interativa que mostra a duração das viagens de acordo com a nacionalidade e o gênero dos viajantes.
- **Tipos de Transporte**: Análise dos tipos de transporte mais utilizados durante as viagens, com destaque para os transportes mais frequentes.
- **Custos por País**: A análise de custos totais por país foi realizada, evidenciando os países que geram os maiores custos para os viajantes.

### 5. Dashboard no Power BI

- A análise também foi complementada por um dashboard interativo no **Power BI**, onde as visualizações e insights podem ser explorados de forma dinâmica.

## Tecnologias Utilizadas

- **Python**: Para análise e manipulação dos dados, utilizando bibliotecas como:
  - **Pandas** para manipulação de dados.
  - **Seaborn** e **Matplotlib** para visualizações estáticas.
  - **Plotly** para visualizações interativas.
- **Power BI**: Para criação de um dashboard interativo e visualização em tempo real dos dados.

## Resultados

A análise revelou padrões interessantes sobre a distribuição de idade, preferências de transporte e acomodação, e o custo de viagens por país. Essas informações podem ser úteis para empresas de turismo e viajantes que buscam entender melhor os custos e comportamentos em viagens internacionais.

---

Se você tiver algum feedback ou sugestão, fique à vontade para perguntar em alguma das minhas redes de contato.


