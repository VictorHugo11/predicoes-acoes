# Análise Preditiva de Preços das Ações com Redes Neurais LSTM

Este projeto visa prever os preços futuros das ações da Petrobras (PETR4.SA) usando Redes Neurais LSTM, uma técnica avançada de Machine Learning.

## Visão Geral

Neste projeto, utilizamos dados históricos de fechamento diário da Petrobras desde 2010 para treinar um modelo de Rede Neural LSTM. A análise foi realizada em Python, utilizando a biblioteca Keras.

## Passos Principais

1. **Coleta e Preparação de Dados:** Utilizamos o pacote yfinance para coletar os dados históricos de preços de fechamento da PETR4.SA e normalizamos esses dados para escalá-los entre 0 e 1.

2. **Construção do Modelo LSTM:** Desenvolvemos um modelo de Rede Neural LSTM com Keras, treinado com os dados históricos para prever os preços futuros das ações.

3. **Avaliação do Modelo:** Após o treinamento, o modelo foi utilizado para prever os preços futuros e comparado com os valores reais para avaliar sua precisão.

4. **Análise de Performance:** Métricas como erro médio quadrático (RMSE) e taxa de acerto do modelo ao prever a direção do mercado foram calculadas para analisar o desempenho.

## Resultados

As previsões para os dias 20 a 27 de dezembro de 2023 foram comparadas com os valores reais, evidenciando algumas discrepâncias pontuais.
