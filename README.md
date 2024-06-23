# Previsão de Câncer de Pulmão

Este projeto é uma análise e implementação de um modelo de machine learning para previsão de câncer de pulmão. Foi desenvolvido para fins educacionais, com o objetivo de aprender e praticar técnicas de preprocessamento de dados, treinamento de modelos e avaliação de desempenho.

## Estrutura do Projeto

- **src/**
  - `eda.ipynb`: Notebook usado para explorar e entender melhor o dataset.
  - `predict.ipynb`: Notebook usado para preprocessamento dos dados, treinamento, teste, previsão e avaliação do modelo. Também utilizado para validação cruzada e cálculo de métricas de precisão.

## Algoritmo Utilizado

- **XGBoost**: O modelo de aprendizado utilizado é o XGBoost, um potente algoritmo de boosting baseado em árvores de decisão, conhecido por sua alta performance em problemas de classificação e regressão.

## Preprocessamento

- **Pipeline de Preprocessamento**: Foi criada uma pipeline que utiliza `OneHotEncoder` para variáveis categóricas e `StandardScaler` para variáveis numéricas. Esse pipeline separa e processa as variáveis de forma adequada antes de alimentá-las ao modelo.

## Visualizações

- **Matplotlib**: Utilizado para criar visualizações dos dados e dos resultados do modelo.
- **Sklearn**: Utilizado para validação cruzada com KFold e outras métricas de avaliação.

## Validação

- **Validação Cruzada**: Utilizou-se a técnica de KFold para validar a performance do modelo de forma robusta, garantindo que o modelo generalize bem para novos dados.

## Objetivo

Este projeto é um projeto pequeno e foi desenvolvido para fins educacionais, visando o meu aprendizado em machine learning e análise de dados.

## Contribuição

Este projeto é destinado ao aprendizado pessoal. Contribuições são bem-vindas para melhorar o código e a abordagem utilizada.