# README - Classificação, Validação de Modelos e Métricas de Avaliação

## Descrição
Este repositório contém o Jupyter Notebook desenvolvido durante um curso sobre classificação, validação de modelos e métricas de avaliação. O notebook inclui uma variedade de técnicas e métodos utilizados para a construção e avaliação de modelos de classificação.

## Conteúdo do Notebook
- **Preparação de Dados**: Código para carregar e preparar os dados para modelagem (`dados`, `x`, `y`).
- **Manipulação de Dados**: Técnicas para balanceamento de classes utilizando métodos de oversampling (`oversample`) e undersampling (`undersample`).
- **Modelagem**: Definição e treinamento do modelo de classificação (`modelo`).
- **Validação Cruzada**: Implementação de validação cruzada para avaliação de modelos (`cv_resultados`, `kf`, `skf`).
- **Métricas de Avaliação**: Cálculo da média e desvio padrão das métricas de desempenho (`media`, `desvio_padrao`), e uso da matriz de confusão (`matriz_confusao`).
- **Visualizações**: Geração de gráficos para visualização dos resultados (`visualizacao`).
- **Funções Auxiliares**: Função para cálculo de intervalo de confiança (`intervalo_conf`).

## Como Usar
Para executar este notebook, é recomendado utilizar um ambiente Python com suporte para Jupyter. É necessário instalar todas as dependências listadas abaixo.

## Dependências
- `pandas`
- `sklearn.tree.DecisionTreeClassifier`
- `sklearn.model_selection`
- `sklearn.metrics`
- `imblearn.over_sampling.SMOTE`
- `imblearn.under_sampling.NearMiss`
- `imblearn.pipeline.Pipeline`

## Autor
- Lucas Knust
