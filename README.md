# Regressão Linear Simples usando Jupyter Notebook



(https://img.shields.io/badge/Feito%20com-Python-blue)
(https://img.shields.io/badge/Utilizando-Jupyter%20Notebook-orange)



Este repositório contém um exemplo simples de implementação de Regressão Linear usando Python em um notebook Jupyter, focando em prever salários com base na experiência.

## Dependências

 Bibliotecas usadas:
 
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn

## Instruções de Uso

- Clone este repositório para sua máquina local.
- Abra o arquivo 'regressao_linear.ipynb' em seu Jupyter Notebook para ver os resultados e interagir com o código.

## Passos no Notebook

1. **Importando as bibliotecas:** Importe as bibliotecas necessárias, incluindo NumPy, pandas e Matplotlib.

2. **Importando o conjunto de dados:** Importe o conjunto de dados 'Salary_Data.csv' usando pandas e divida-o em variáveis de entrada e saída (x e y).

3. **Dividindo o conjunto de dados:** Use a função 'train_test_split' do scikit-learn para dividir o conjunto de dados em dados de treinamento e dados de teste.

4. **Treinando o modelo de regressão linear:** Treine o modelo de Regressão Linear com o conjunto de dados de treinamento usando a classe 'LinearRegression' do scikit-learn.



5. **Previsão de resultados:** Com o modelo treinado, faça previsões nos dados de teste e armazene os resultados na variável 'y_pred'.

6. **Visualizando os resultados:** Use Matplotlib para criar gráficos que mostram os resultados do conjunto de treinamento e do conjunto de testes.


