# 📊 Case Churn - DataMaster

[![GitHub last commit](https://img.shields.io/github/last-commit/felipesbonatti/Case.Datamaster?style=flat-square)](https://github.com/felipesbonatti/Case.Datamaster)
[![GitHub repo size](https://img.shields.io/github/repo-size/felipesbonatti/Case.Datamaster?style=flat-square)](https://github.com/felipesbonatti/Case.Datamaster)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Logo GitHub" width="100">
</p>

---

## 📌 Sobre o Projeto

Este repositório apresenta um **estudo de caso sobre previsão de churn (evasão de clientes)** em um serviço de streaming. O objetivo principal é **avaliar a probabilidade de churn nos próximos três meses** e, com base nessa previsão, implementar políticas e ações para evitar a perda de clientes.

O projeto está dividido em duas partes principais:
1. **Previsão de Churn:** Desenvolvimento de um modelo preditivo utilizando técnicas de machine learning.
2. **Análise Não Supervisionada:** Análise comportamental dos clientes para identificar padrões e segmentos.

---

## 🎯 Objetivo

O objetivo deste estudo é **prever a evasão de clientes (churn)** e **entender os fatores que influenciam essa decisão**. Para isso, foram considerados os seguintes aspectos:

- **Definição do Alvo (Target):**
  - O cliente está inativo?
  - Cancelou seu plano?
  - Não ouviu música nos últimos três meses?

- **Hipóteses Analisadas:**
  - Comportamento histórico do cliente (valor da assinatura, quantidade de música ouvida).
  - Características socioeconômicas (idade, gênero, cidade, canal de aquisição).
  - Relação entre a quantidade de música ouvida no mês anterior e o churn.
  - Dias desde o registro (clientes mais novos têm maior propensão ao churn?).

---

## ⚙️ Solução Entregue

### 1. **Modelo de Previsão de Churn**
   - **Análise Exploratória:** Compreensão do comportamento dos dados e suas relações.
   - **Seleção de Features:** Identificação das variáveis mais relevantes para o modelo.
   - **Treinamento do Algoritmo:** Utilização de técnicas de machine learning para prever churn.
   - **Hiperparametrização:** Ajuste dos parâmetros do modelo para melhorar a precisão.
   - **Previsão e Conclusão:** Avaliação do modelo e interpretação dos resultados.

### 2. **Análise Não Supervisionada**
   - **Normalização e PCA:** Redução da dimensionalidade dos dados.
   - **Amostragem e K-means:** Segmentação dos clientes em grupos com comportamentos semelhantes.

---

## 📊 Resultados

O projeto resultou em:
- **Modelo Preditivo de Churn:** Capaz de identificar clientes com alta probabilidade de evasão.
- **Segmentação de Clientes:** Identificação de grupos com comportamentos distintos.
- **Insights Estratégicos:** Recomendações para reduzir a taxa de churn e melhorar a retenção de clientes.

---

## 🛠️ Tecnologias Utilizadas

<div style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn">
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white" alt="PySpark">
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
</div>

- **Linguagem de Programação:** [Python](https://www.python.org/)
- **Bibliotecas:** Pandas, Scikit-learn, PySpark
- **Banco de Dados:** SQL
- **Ferramentas de Análise:** Jupyter Notebook, PCA, K-means


