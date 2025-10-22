# Projetos de Mineração de Dados (Data Mining Projects)

Este repositório contém os projetos e atividades desenvolvidos para a disciplina de Mineração de Dados na UFC. O foco é a aplicação prática de pipelines de Data Science, desde a limpeza até a modelagem preditiva.

---

## Projeto 1: Análise Preditiva de Hábitos Alimentares

Este projeto utiliza o dataset "Food Choices" para construir um modelo de classificação capaz de prever a autopercepção de sobrepeso de estudantes.

### 1. Limpeza e Pré-processamento
* **Notebook:** `[Exercicio_Limpeza_de_Dados.ipynb]`
* **Descrição:** Tratamento de valores ausentes (imputação por mediana/moda), remoção de duplicatas e transformação de tipos de dados.
* **Tecnologias:** Python, Pandas.

### 2. Modelagem e Classificação
* **Notebook:** `[Exercicio_Classificacao_de_Dados.ipynb]`
* **Descrição:** Comparação de 6 algoritmos de classificação (Random Forest, SVM, k-NN, etc.) para prever a autopercepção de peso. O processo incluiu o uso de Pipelines do Scikit-learn, Validação Cruzada (Cross-Validation) e otimização com GridSearchCV.
* **Tecnologias:** Python, Scikit-learn, Pandas.

### Resultado Principal
O modelo Random Forest ajustado obteve o melhor desempenho (F1-Score de 0.79), demonstrando um pipeline robusto desde a limpeza até a predição.

---
