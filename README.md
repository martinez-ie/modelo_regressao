# modelo_regressao

🔢 Projeto: Modelo de Regressão para Previsão de Preço
Este projeto tem como objetivo construir um modelo preditivo de regressão para estimar o preço de produtos com base em variáveis como categoria, avaliação dos usuários e presença de desconto. A proposta simula um cenário comum no varejo, em que a precificação precisa ser analisada com apoio de dados para garantir competitividade e lucratividade.

🎯 Objetivo
Desenvolver e avaliar modelos de regressão capazes de prever o preço de produtos a partir de características disponíveis em um dataset fictício. O foco principal foi treinar modelos supervisionados, comparar seus desempenhos e interpretar os resultados obtidos para posterior tomada de decisão.

🧪 Etapas do Projeto
Análise Exploratória de Dados (EDA)

Leitura do dataset com pandas.

Análise descritiva: verificação de colunas, tipos de variáveis, valores nulos e distribuição dos dados.

Gráficos com seaborn e matplotlib para identificar correlações e outliers.

Limpeza e Pré-processamento

Tratamento de valores ausentes.

Codificação de variáveis categóricas com LabelEncoder.

Normalização com MinMaxScaler para manter os dados em uma escala apropriada à modelagem.

Modelagem

Aplicação de Regressão Linear como baseline.

Implementação de modelos mais robustos como Random Forest Regressor e XGBoost.

Divisão dos dados em treino e teste com train_test_split.

Avaliação de Desempenho

Métricas utilizadas: R² Score, MAE (Erro Absoluto Médio) e MSE (Erro Quadrático Médio).

Visualização dos erros com gráficos de dispersão e análise de resíduos.

🛠️ Ferramentas e Tecnologias Utilizadas
Python (Jupyter Notebook)

Bibliotecas:

pandas e numpy para manipulação de dados

matplotlib e seaborn para visualização

scikit-learn para modelagem e métricas

xgboost para algoritmos avançados de regressão

📈 Resultados
Os modelos foram comparados com base em suas métricas de performance, sendo o Random Forest Regressor o que apresentou melhor capacidade de generalização no conjunto de teste. Além disso, foi possível observar como variáveis como avaliação e desconto influenciam diretamente no preço dos produtos.

💡 Aprendizados
Esse projeto me permitiu aprofundar conhecimentos em:

Engenharia de atributos e preparação de dados para modelos supervisionados.

Comparação entre diferentes algoritmos de regressão.

Interpretação crítica de métricas e visualizações para refinar modelos.
