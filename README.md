# Projeto de Predição de Evasão de Alunos

Este projeto tem como objetivo construir um modelo de Machine Learning para prever a evasão de alunos com base em seu engajamento acadêmico e participação em avaliações do tipo SM. O projeto segue as etapas típicas de um projeto de Machine Learning:

## Pré-requisitos

Antes de executar o notebook, você precisará:

1. **Python 3.6 ou superior.**
2. **As seguintes bibliotecas do Python: pandas, numpy, matplotlib, scikit-learn.** Você pode instalar essas bibliotecas usando pip:



```pip install pandas numpy matplotlib scikit-learn```


3. **Os dados do aluno no formato CSV.** Os arquivos devem ser nomeados `alunos_teste.csv`, `acessos_conteudo_teste.csv` e `provas_teste.csv` e colocados no mesmo diretório do notebook.

## Execução

Para executar o notebook, abra-o em uma instância do Jupyter Notebook e execute as células em ordem.

## Fluxo de Trabalho

1. **Importação das bibliotecas necessárias:** Importamos todas as bibliotecas necessárias para o projeto.
2. **Carregamento dos dados:** Carregamos os dados brutos dos arquivos CSV.
3. **Análise Exploratória de Dados (EDA):** Realizamos uma análise exploratória dos dados, que pode incluir a criação de histogramas e outros gráficos adequados.
4. **Pré-processamento dos dados:** Agrupamos os dados por aluno-disciplina e criamos os recursos necessários para o modelo.
5. **União das tabelas:** Unimos as três tabelas de dados em uma única tabela por aluno-disciplina.
6. **Normalização dos dados:** Normalizamos os dados usando o `StandardScaler` do `sklearn`.
7. **Separação dos dados em treino e teste:** Separamos os dados em conjuntos de treino e teste.
8. **Seleção do modelo:** Escolhemos o `RandomForestClassifier` do `sklearn` como nosso algoritmo de Machine Learning.
9. **Treinamento do modelo:** Treinamos o modelo usando os dados de treinamento.
10. **Avaliação do modelo:** Avaliamos a performance do modelo usando os dados de teste.

