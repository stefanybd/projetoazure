# projetoazure
Projeto Azure
Este projeto tem como objetivo prever as vendas com base nos gastos com marketing utilizando um modelo de regressão linear.
Passos para a construção do modelo
1. Coleta e Preparação dos Dados

O primeiro passo foi criar um conjunto de dados fictício contendo duas variáveis:

    Gastos com Marketing (em milhares de unidades monetárias)
    Vendas (em milhares de unidades vendidas)

Para este exemplo, a relação entre os gastos e as vendas é linear, ou seja, à medida que o gasto com marketing aumenta, as vendas também aumentam.
2. Divisão dos Dados em Treinamento e Teste

Os dados foram divididos em 80% para treinamento e 20% para teste. Essa divisão é fundamental para avaliar a capacidade do modelo de generalizar para novos dados.
3. Construção do Modelo

Utilizamos a técnica de regressão linear, que é adequada quando há uma relação linear entre as variáveis. A regressão linear tenta ajustar uma linha reta que minimize a soma dos erros quadrados entre as previsões do modelo e os dados reais.
4. Treinamento do Modelo

O modelo foi treinado utilizando a função fit da biblioteca scikit-learn.
5. Avaliação do Modelo

Utilizamos o erro médio quadrado (MSE) para avaliar a performance do modelo. O MSE nos dá uma indicação de quão distantes as previsões estão dos valores reais. Quanto menor o valor de MSE, melhor o modelo.
6. Visualização dos Resultados

Os resultados foram visualizados através de um gráfico onde:

    Os pontos azuis representam os dados reais de vendas.
    A linha vermelha mostra as previsões feitas pelo modelo de regressão linear.

Como Rodar o Código

    Instale as dependências necessárias:
    pip install numpy pandas matplotlib scikit-learn
    
Execute o código:

      python nome_do_arquivo.py

O gráfico será exibido e o erro médio quadrado será mostrado no console.

Resultados Esperados

O modelo deve ser capaz de prever com precisão as vendas com base nos gastos com marketing, desde que a relação entre as variáveis seja predominantemente linear.
3. Exemplo de Saída Esperada

A execução do código geraria um gráfico mostrando como o modelo se ajusta aos dados. Além disso, o MSE será impresso no console.
