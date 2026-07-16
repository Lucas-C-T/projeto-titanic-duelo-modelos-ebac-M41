# Desafio Duelo de Modelos - Titanic

## 🎯 Objetivo
Este projeto faz parte do curso de Data Science da EBAC e tem como objetivo a aplicação prática de técnicas avançadas de Machine Learning para superar resultados de referência no desafio clássico de sobrevivência do Titanic (Kaggle).

## 🛠️ Tecnologias Utilizadas
- **Linguagem**: Python 3.9+
- **Manipulação de Dados**: Pandas, NumPy
- **Visualização**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn, XGBoost, imblearn (SMOTE)

## 📊 Metodologia
O fluxo de trabalho foi estruturado para maximizar a precisão do modelo através de:

1. **Análise Exploratória (EDA)**: Identificação de padrões, tratamento de valores ausentes (como em `Age` e `Fare`) e análise de correlação.
2. **Feature Engineering**: Transformação de variáveis categóricas (One-Hot Encoding em `Cabin_deck` e `Embarked`) e conversão de gênero em formato binário.
3. **Pré-processamento**: Aplicação de técnicas de padronização/normalização e gestão de classes (incluindo exploração de balanceamento).
4. **Modelagem**: Implementação e teste de algoritmos (SVM, Random Forest, XGBoost).
5. **Otimização**: Uso de `GridSearchCV`.
6. **Submissão**: Geração de previsões otimizadas para o conjunto de teste do Kaggle.

---
*Projeto desenvolvido como parte da atividade "Duelo de Modelos" da EBAC.*
