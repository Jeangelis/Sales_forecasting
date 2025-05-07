# **🏷️ Sales forecasting: melhoria de previsões com machine learning**

A previsão de vendas é uma atividade essencial para empresas de varejo, pois impacta diretamente na gestão de estoque, planejamento de compras e maximização de receitas. 

## 📌 Contexto

Este projeto foi pensado para refletir um desafio comum enfrentado por empresas no setor de varejo, que é a necessidade de estimativas mais precisas para embasar decisões estratégicas de estoque, logística e marketing. Para isso foram avaliados diferentes modelos a fim de analisar os ganhos de acurácia das previsões.

## 📂 Dataset

A base de dados utilizada é proveniente da competição ["Store Sales - Time Series Forecasting"](https://www.kaggle.com/competitions/store-sales-time-series-forecasting) do Kaggle, e contém registros diários de vendas, informações sobre produtos, lojas, promoções e feriados.

## 🔍 Etapas do projeto

1. **Aquisição e pré-processamento dos dados:** importação, limpeza, tratamento de valores faltantes e criação de variáveis temporais.
2. **Análise exploratória dos dados:** visualização de tendências, sazonalidade, impacto de feriados e outras variáveis relevantes.
3. **Modelagem:** ajuste dos modelos SARIMA, Prophet e XGBoost.
4. **Avaliação dos modelos:** comparação do desempenho dos modelos com base em métricas como correlação, viés, RMSE e RMSLE.
5. **Discussão dos resultados:** análise das implicações práticas das previsões, limitações dos modelos e próximos passos.

## ✅ Resultados

O XGBoost apresentou o melhor desempenho, com menor erro e viés, seguido pelo Prophet e SARIMA. Os modelos demonstraram potencial para auxiliar na gestão de estoque, planejamento de compras, alocação de recursos e marketing.

## 🛠️ Tecnologias utilizadas

* Python
* Pandas
* Scikit-learn
* Statsmodels
* Prophet
* XGBoost
* Matplotlib
* Seaborn

## Observações adicionais

* Os códigos e visualizações geradas neste projeto podem ser encontrados no notebook 'Sales_forecasting.ipynb'.
* Sinta-se à vontade para entrar em contato caso tenha alguma dúvida ou sugestão.

Espero que este projeto seja útil e informativo! 😉
