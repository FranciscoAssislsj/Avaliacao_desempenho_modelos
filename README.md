# Avaliação de Modelos de Regressão Não Linear

Este projeto compara diferentes modelos de Regressão Não Linear para prever o preço de imóveis com base em diversas variáveis da base de dados.

## Objetivo:
Avaliar o desempenho dos modelos de RandomForestRegressor, AdaBoostRegressor e GradientBoostingRegressor e selecionar o melhor com base em métricas de desempenho.

## Tecnologias Utilizadas:
Python, Pandas, NumPy, Scikit-learn

## Dados:
O dataset utilizado contém informações sobre imóveis, incluindo:
Variáveis categóricas e numéricas que influenciam no preço.
SalePrice: O preço final do imóvel (variável alvo).

## Métricas:
R² Score (Coeficiente de Determinação)
MAE (Erro Absoluto Médio)
MSE (Erro Quadrático Médio)

## Conclusão:
Gradient Boosting teve o melhor R² (97,1%), indicando que explica melhor a variação dos preços das casas.
Menor MAE (17.853)
Menor MSE (778M)
