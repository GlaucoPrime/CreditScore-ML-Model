# 🏦 CreditScore-ML-Model: Previsão de Score de Crédito com Python

## 🌟 Visão Geral

Este projeto utiliza Machine Learning (Aprendizado de Máquina) para prever o Score de Crédito de clientes de um banco (classificação em 'Ruim', 'Ok', 'Bom'). O objetivo é criar um modelo preditivo robusto para auxiliar nas decisões de empréstimo e oferta de crédito, minimizando o risco de inadimplência.

## ✨ Tecnologias & Modelo

* **Biblioteca Principal:** **Scikit-learn (sklearn)**.
* **Tratamento de Dados:** **Pandas** para importação e **LabelEncoder** para transformar colunas de texto (categóricas) em valores numéricos.
* **Modelos de Classificação:**
    * **RandomForestClassifier** (Árvore de Decisão) - Escolhido como **melhor modelo** com acurácia de ~83%.
    * **KNeighborsClassifier** (Vizinhos Próximos) - Usado como comparativo.
* **Métrica:** **Accuracy Score** para avaliar o desempenho dos modelos.

## 🛠️ Passos do Projeto

1.  Importação e Análise da base de dados (`clientes.csv`).
2.  Tratamento de colunas de texto (`profissao`, `mix_credito`, `comportamento_pagamento`) com **LabelEncoder**.
3.  Separação dos dados em Treino e Teste (`train_test_split`).
4.  Treinamento e Comparação dos modelos **Random Forest** e **KNN**.
5.  Previsão do Score de Crédito para novos clientes (`novos_clientes.csv`).

---
