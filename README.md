# Previsão de Preços das Ações da Petrobras com Redes Neurais LSTM 📈

Este repositório contém o código e a documentação de um projeto desenvolvido para prever os preços das ações da Petrobras (PETR4.SA) utilizando redes neurais LSTM (Long Short-Term Memory). O objetivo principal foi criar um modelo capaz de analisar dados históricos de preços e prever o movimento futuro das ações.

## 📋 Visão Geral do Projeto

- **Dados Utilizados:** Dados históricos de preços de fechamento das ações da Petrobras, abrangendo o período de 2010 a 2024.
- **Modelo:** Rede Neural LSTM construída usando Keras, com múltiplas camadas para capturar padrões temporais nos dados.
- **Divisão dos Dados:** 80% dos dados foram utilizados para treinamento e 20% para teste.
- **Escala dos Dados:** Os dados foram escalados para um intervalo de 0 a 1 para melhorar a eficiência do modelo.

## 🚀 Resultados

- **Precisão Direcional:** O modelo acertou a direção (se a ação subiria ou cairia) em aproximadamente 50% dos casos.
- **Expectativa de Lucro:** A expectativa de lucro das previsões acertadas foi maior do que a perda causada pelos erros, resultando em um ganho sobre perda de cerca de 8,8%.
- **Erro Médio Quadrático (RMSE):** O erro médio quadrático foi calculado para avaliar a precisão das previsões.

## 📈 Visualização

O projeto inclui gráficos que comparam os preços reais das ações com as previsões feitas pelo modelo. Esses gráficos demonstram como o modelo se comporta ao longo do tempo.

## 📜 Considerações Finais

Embora o modelo apresente resultados promissores, é fundamental entender que ele não oferece garantias de 100% de assertividade. Modelos preditivos como este devem ser utilizados como ferramentas auxiliares na análise do mercado, e não como única base para decisões de investimento. O mercado de ações é dinâmico e influenciado por diversos fatores imprevisíveis.

<<<<<<< HEAD
## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Keras
- Matplotlib
- Yahoo Finance API
=======
As previsões para os dias 20 a 27 de dezembro de 2023 foram comparadas com os valores reais, evidenciando algumas discrepâncias pontuais.
>>>>>>> e0dbb36e1018ee24914c3c91d405718fcb8200d4
