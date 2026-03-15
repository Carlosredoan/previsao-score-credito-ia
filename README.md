# Previsão de Score de Crédito com Inteligência Artificial 📊

Este projeto foi desenvolvido com o objetivo de criar um modelo de Machine Learning capaz de prever a classificação de crédito de clientes (Bom, Médio ou Ruim) com base em seu histórico financeiro e perfil demográfico.

## 🚀 Tecnologias Utilizadas
* **Python 3.x**
* **Pandas**: Para manipulação e análise da base de dados.
* **Scikit-Learn**: Para a criação, treinamento e avaliação dos modelos de IA.
* **Jupyter Notebook**: Ambiente de desenvolvimento para os testes e visualização.

## 🧠 O Problema
O desafio era analisar uma base histórica de 100.000 clientes e identificar padrões que definem o score de crédito. Após o tratamento dos dados, o modelo deve ser capaz de classificar novos clientes automaticamente, auxiliando na tomada de decisão para concessão de crédito.

## 🛠️ Passo a Passo do Projeto
1. **Tratamento de Dados**: Conversão de variáveis categóricas (texto) em numéricas utilizando `LabelEncoder`.
2. **Divisão de Dados**: Separação da base em conjuntos de Treino (70%) e Teste (30%).
3. **Modelagem**: Treinamento de dois modelos distintos:
    * **Random Forest (Árvore de Decisão)**
    * **KNN (K-Nearest Neighbors)**
4. **Avaliação**: Comparação da acurácia dos modelos para escolher o mais eficiente.

## 📈 Resultados
O modelo de **Árvore de Decisão** apresentou a melhor performance, atingindo uma **acurácia de aproximadamente 82.4%**, superando o modelo KNN. Com o modelo campeão, foi possível prever com sucesso o score de novos clientes que entraram na base.