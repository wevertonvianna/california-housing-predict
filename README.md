# california-housing-predict

Previsão de Preços de Casas na Califórnia

O que é o projeto: Um modelo de regressão para prever o preço médio de imóveis em distritos da Califórnia usando dados do censo de 1990.

O que foi feito:

Limpeza de dados (tratamento de valores nulos na coluna total_bedrooms).

Transformação de variáveis categóricas usando One-Hot Encoding.

Divisão dos dados em 80% treino e 20% teste.

Modelos Testados e Resultados:

Regressão Linear: RMSE de ~US$ 68.000 (R²: 0.62)

Random Forest Regressor: RMSE de US$ 48.977,75 (R²: 0.8169)

Conclusão: O modelo baseado em árvores (Random Forest) capturou melhor as relações complexas dos dados, reduzindo o erro médio em quase US$ 20.000.
