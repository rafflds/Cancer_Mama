# Breast Cancer Data Analysis Project

[![Python](https://img.shields.io/badge/python-3.8+-blue.svg?logo=python)](https://www.python.org/downloads/)
[![tkinter](https://img.shields.io/badge/tkinter-GUI-orange.svg?logo=python)](https://docs.python.org/3/library/tkinter.html)
[![scikit-learn](https://img.shields.io/badge/scikit_learn-ML-brightgreen.svg?logo=scikit-learn)](https://scikit-learn.org/stable/)
[![pandas](https://img.shields.io/badge/pandas-DataAnalysis-blueviolet.svg?logo=pandas)](https://pandas.pydata.org/)

**Um projeto de ciência de dados com interface gráfica para análise do dataset Breast Cancer do scikit-learn.**

<p align="center">
  <img src= "![image](https://github.com/user-attachments/assets/7c4e33f1-a900-4b38-961a-c3c084bbe291)"
 alt="GUI Screenshot" width="600">
</p>

## 🚀 Sobre o Projeto

Este projeto tem como objetivo demonstrar um fluxo de trabalho de ciência de dados completo, desde a análise exploratória até a modelagem e avaliação, utilizando o dataset `load_breast_cancer` do scikit-learn. Para facilitar a interação, desenvolvi uma interface gráfica (GUI) com `tkinter`.

### Principais Funcionalidades:

-   **Análise Exploratória de Dados (EDA):**
    -   Exibição de informações básicas (tipo de dados, estatísticas descritivas).
    -   Visualização da distribuição da variável alvo.
    -   Matriz de correlação entre os atributos.
    -   Histogramas de algumas features.
-   **Pré-processamento de Dados:**
    -   Divisão dos dados em conjuntos de treinamento e teste.
    -   Normalização dos dados usando `StandardScaler`.
-   **Modelagem:**
    -   Treinamento de múltiplos modelos de classificação (Regressão Logística, Árvore de Decisão, Random Forest, SVM).
    -   Avaliação do desempenho dos modelos.
-   **Otimização:**
    -   Ajuste de hiperparâmetros do modelo Random Forest com `GridSearchCV`.
-   **Interface Gráfica (GUI):**
    -   Botões para executar as etapas do projeto.
    -   Área de texto para exibir informações e resultados.
    -   Área para exibir gráficos.

## 🛠️ Tecnologias Utilizadas

-   **Python:** Linguagem de programação principal.
-   **scikit-learn:** Biblioteca de machine learning para modelos e pré-processamento.
-   **pandas:** Biblioteca para manipulação e análise de dados.
-   **matplotlib e seaborn:** Bibliotecas para visualização de dados.
-   **tkinter:** Biblioteca para criação da interface gráfica.
-   **numpy:** Biblioteca para operações numéricas.

## 📦 Requisitos

Para executar este projeto, você precisa ter o Python 3.8+ instalado, além das seguintes bibliotecas:

```bash
pip install scikit-learn pandas matplotlib seaborn numpy


💡 Como Usar a Interface
-  Explorar Dados: Exibe informações básicas sobre o dataset, estatísticas descritivas, contagem de classes e gráficos relevantes (contagem de classes e correlação).

-  Pré-processar Dados: Divide os dados em treinamento e teste e normaliza os dados.

-  Treinar Modelos: Treina vários modelos de classificação e exibe os resultados.

-  Otimizar Random Forest: Otimiza os hiperparâmetros do modelo Random Forest usando GridSearchCV e exibe os resultados do modelo otimizado.

-  Mostrar Resultados: Exibe os resultados de desempenho de todos os modelos treinados e do Random Forest otimizado.




