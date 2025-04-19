# Modelo de Projeto: Ciência de Dados

Este modelo de projeto é adequado para iniciantes que estão começando a aprender sobre Ciência de Dados, mas também é útil para quem quer reforçar conceitos e criar um fluxo básico para seus projetos.

## 1. Descrição do Projeto

Objetivo: Prever o preço de casas com base em características como número de quartos, tamanho da casa, localização, etc.

## 2. Dados Utilizados

- **Fonte**: [Kaggle - Preços de Casas](https://www.kaggle.com/)
- **Formato**: CSV
- **Descrição**: Dados sobre características de casas e seus preços de venda.
- **Transformações**: Substituição de valores ausentes por média, conversão de variáveis categóricas para variáveis dummy.

## 3. Metodologia

1. **Coleta de Dados**: Baixamos os dados do Kaggle.
2. **Pré-processamento**: Limpeza dos dados (valores nulos e transformação de variáveis).
3. **Análise Exploratória de Dados (EDA)**: Visualizações simples para entender as distribuições e correlações entre as variáveis.
4. **Modelagem**: Aplicação de Regressão Linear e Árvore de Decisão para prever o preço das casas.
5. **Avaliação**: Usamos a métrica RMSE (Root Mean Squared Error) para avaliar a precisão do modelo.

## 4. Resultados

- **Modelo de Regressão Linear**: RMSE = 25000
- **Modelo de Árvore de Decisão**: RMSE = 20000
- **Conclusão**: A Árvore de Decisão apresentou resultados melhores, com um erro médio menor.

## 5. Conclusões

O modelo de Árvore de Decisão foi eficiente para prever o preço das casas com dados simples. Há espaço para melhorias, como o uso de mais variáveis e ajustes no modelo.

## 6. Como Rodar o Projeto

```bash
# Instalar dependências
pip install -r requirements.txt

# Rodar o script principal
python main.py
