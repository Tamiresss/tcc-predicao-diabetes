# Modelo Preditivo Baseado em Machine Learning para Identificação do Risco de Diabetes Mellitus Tipo 2

## 🎯 Objetivo
Desenvolver e avaliar modelos de aprendizado de máquina para a predição do risco de Diabetes Mellitus Tipo 2 (DM2). O estudo compara diferentes algoritmos de classificação e analisa seu potencial como ferramenta de apoio à identificação precoce de indivíduos em risco.

## 📊 Base de Dados
O estudo utiliza o dataset **Diabetes Health Indicators Dataset**, contendo informações relacionadas à saúde, hábitos de vida e características demográficas dos indivíduos.

🔗 Dataset:
https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset

## 🤖 Algoritmos Avaliados
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- XGBoost

## ⚙️ Metodologia
As principais etapas do projeto foram:

1. Pré-processamento dos dados;
2. Separação em conjuntos de treino e teste;
3. Ajuste de hiperparâmetros utilizando GridSearchCV;
4. Treinamento dos modelos;
5. Avaliação por meio das métricas Accuracy, Precision, Recall, F1-Score e AUC-ROC;
6. Ajuste de limiar;
7. Análise de importância das variáveis.

## 📈 Principais Resultados
O modelo com melhor desempenho foi o **XGBoost**, após o ajuste de limiar, apresentando:

| Métrica | Valor |
|----------|----------|
| Accuracy | 0.7506 |
| Precision | 0.7221 |
| Recall | 0.8278 |
| F1-Score | 0.7714 |
| AUC-ROC | 0.8246 |

## 🔍 Variáveis Mais Importantes
As variáveis que mais influenciaram as predições do modelo XGBoost foram:

1. Pressão alta
2. Saúde geral
3. Colesterol alto
4. Idade
5. Dificuldade para caminhar
6. IMC
