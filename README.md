# Projeto Principia 

## Descrição

Este projeto é uma análise de ciência de dados realizada em Python utilizando Pandas, Matplotlib e Scikit-Learn. Ele realiza várias operações, incluindo importação de dados, pré-processamento, análise exploratória e modelagem.

## Detalhes do Notebook

O notebook realiza as seguintes operações:

1. **Importação das bibliotecas necessárias**: O notebook começa importando todas as bibliotecas necessárias para a análise.

2. **Download de dados**: Em seguida, baixa um arquivo ZIP de um URL especificado e extrai os arquivos contidos.

3. **Carregamento dos dados**: Os dados são carregados em dataframes do Pandas a partir dos arquivos CSV extraídos.

4. **Análise Exploratória de Dados (EDA)**: Estatísticas descritivas e histogramas são gerados para cada coluna no dataframe de alunos.

5. **Pré-processamento dos dados**: Os valores ausentes são preenchidos com a média e as variáveis categóricas são codificadas usando a função `get_dummies` do Pandas.

## Uso

Para utilizar este notebook, você precisará ter as bibliotecas Python listadas no notebook instaladas em seu ambiente. Você também precisará ter acesso à internet para baixar o arquivo ZIP contendo os dados.
os arquivos CSV.
3. **Análise Exploratória de Dados (EDA):** Realizamos uma análise exploratória dos dados, que pode incluir a criação de histogramas e outros gráficos adequados.
4. **Pré-processamento dos dados:** Agrupamos os dados por aluno-disciplina e criamos os recursos necessários para o modelo.
5. **União das tabelas:** Unimos as três tabelas de dados em uma única tabela por aluno-disciplina.
6. **Normalização dos dados:** Normalizamos os dados usando o `StandardScaler` do `sklearn`.
7. **Separação dos dados em treino e teste:** Separamos os dados em conjuntos de treino e teste.
8. **Seleção do modelo:** Escolhemos o `RandomForestClassifier` do `sklearn` como nosso algoritmo de Machine Learning.
9. **Treinamento do modelo:** Treinamos o modelo usando os dados de treinamento.
10. **Avaliação do modelo:** Avaliamos a performance do modelo usando os dados de teste.

