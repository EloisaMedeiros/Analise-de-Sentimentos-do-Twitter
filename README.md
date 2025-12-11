# Objetivo deste projeto
Este repositório apresenta uma análise de sentimentos baseada em tweets de usuários comentando sobre filmes.
O foco principal do projeto é:
- Limpeza de dados textuais
- Classificação de sentimentos (positivo, negativo e neutro)
- Criação de visualizações no Power BI

# Analise de Sentimentos sobre filmes no Twitter
Este projeto realiza uma análise de sentimentos utilizando um dataset fornecido pela Universidade de Michigan, disponibilizado no Kaggle, contendo posts do Twitter sobre opiniões de usuários a respeito de filmes.

# Limpeza e Preparação dos dados
## Pré-processamento com NLTK
A primeira etapa de tratamento dos dados foi realizada em Python utilizando a biblioteca NLTK, onde foram aplicadas técnicas para limpeza textual, como:
- Remoção de stopwords
- Tokenização
- Normalização do texto
- Preparação para classificação dos sentimentos (positivo, negativo e neutro)

## Transformações no Power Query (Power BI)
Após o pré-processamento inicial, o restante da limpeza foi concluído no Power Query, onde:
- Colunas foram ajustadas
- Valores inconsistentes foram tratados
- Criou-se uma coluna de Datas com dados sintéticos, permitindo a construção de visualizações temporais (gráfico de linha de evolução dos sentimentos)

# Tecnologias Utilizadas
- Python
- NTTK
- Power BI
- Power Query
- Kaggle (fonte dos dados)
