<p align="center">
  <img src="https://github.com/martinez-ie/modelo_regressao/blob/main/imagens/banner_regressao.png" alt="Banner do Projeto" width="100%">
</p>

# 🧠 Modelo de Regressão para Previsão de Preço

Este projeto tem como objetivo construir um modelo preditivo de regressão para estimar o preço de produtos com base em variáveis como categoria, avaliação dos usuários e presença de desconto. A proposta simula um cenário comum no varejo, em que a precificação precisa ser analisada com apoio de dados para garantir competitividade e lucratividade.

---

## 📌 Índice

- [🎯 Objetivo](#-objetivo)
- [🧪 Etapas do Projeto](#-etapas-do-projeto)
- [🛠️ Tecnologias e Ferramentas Utilizadas](#️-tecnologias-e-ferramentas-utilizadas)
- [📈 Resultados](#-resultados)
- [💡 Aprendizados](#-aprendizados)
- [🔗 Acesse](#-acesse)

---

## 🎯 Objetivo

Desenvolver e avaliar modelos de regressão capazes de prever o preço de produtos a partir de características disponíveis em um dataset fictício. O foco principal foi treinar modelos supervisionados, comparar seus desempenhos e interpretar os resultados para uma tomada de decisão mais assertiva.

---

## 🧪 Etapas do Projeto

1. **Análise Exploratória de Dados (EDA)**
   - Leitura do dataset com `pandas`.
   - Análise descritiva: colunas, tipos de variáveis, valores nulos e distribuição dos dados.
   - Visualizações com `seaborn` e `matplotlib` para identificar padrões, outliers e correlações.

2. **Limpeza e Pré-processamento**
   - Tratamento de valores ausentes.
   - Codificação de variáveis categóricas com `LabelEncoder`.
   - Normalização com `MinMaxScaler`.

3. **Modelagem**
   - Implementação da **Regressão Linear** como baseline.
   - Aplicação de modelos mais robustos como **Random Forest Regressor** e **XGBoost**.
   - Divisão dos dados em treino e teste com `train_test_split`.

4. **Avaliação de Desempenho**
   - Métricas: `R² Score`, `MAE` (Erro Absoluto Médio) e `MSE` (Erro Quadrático Médio).
   - Gráficos de dispersão e análise de resíduos para avaliação visual dos erros.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- **Python** (Jupyter Notebook)
- **Bibliotecas**:
  - `pandas`, `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn`
  - `xgboost`

---

## 📈 Resultados

Os modelos foram comparados por meio de suas métricas de performance. O **Random Forest Regressor** se destacou com melhor capacidade de generalização. A análise indicou forte influência das variáveis de avaliação e desconto no preço final do produto.

---

## 💡 Aprendizados

- Prática com engenharia de atributos e normalização de dados.
- Comparação entre diferentes algoritmos de regressão.
- Interpretação de métricas e visualizações para aprimoramento dos modelos.

---

## 🔗 Acesse

📂 [Repositório no GitHub](https://github.com/martinez-ie/modelo_regressao)

---
