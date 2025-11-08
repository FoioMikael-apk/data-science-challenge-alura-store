# data-science-challenge-alura-store
1. O Desafio
O Sr. João, proprietário da rede Alura Store, possui quatro lojas, mas deseja vender uma delas para obter capital e investir em um novo negócio.

Objetivo: Atuando como analista de dados, nossa missão é analisar o desempenho das quatro lojas com base em métricas-chave e, ao final, gerar um relatório com uma recomendação clara de qual loja deve ser vendida.

2. 🗂️ Os Dados
A análise foi realizada a partir de quatro conjuntos de dados distintos (.csv), cada um representando uma das lojas:

loja_1.csv

loja_2.csv

loja_3.csv

loja_4.csv

O notebook (AluraStoreBrasil.ipynb) carrega esses arquivos diretamente do repositório original do desafio.

3. 📈 Metodologia da Análise
A análise comparativa foi conduzida no notebook Google Colab, avaliando as quatro lojas com base nas cinco métricas principais:

Faturamento Total: Soma do valor de todas as transações (coluna Preço).

Vendas por Categoria: Contagem de transações por Categoria do Produto para entender o mix de produtos de cada loja.

Média de Avaliação: Média da Avaliação da compra (0-5) para medir a satisfação do cliente.

Produtos Menos Vendidos: Contagem dos produtos com o menor número de transações (identificação de "estoque parado").

Custo Médio do Frete: Média do valor da coluna Frete.

4. 🛠️ Ferramentas Utilizadas
Python

Pandas: Para carregamento, limpeza e análise dos dados.

Matplotlib: Para a criação das visualizações (gráficos de barras e pizza).

Google Colab: Como ambiente de desenvolvimento (notebook).

5. 🎯 Conclusão e Recomendação
Após a análise detalhada, a recomendação para o Sr. João é a venda da Loja 3.

Principais Descobertas que Justificam a Recomendação:
Menor Faturamento: A Loja 3 apresentou o pior desempenho financeiro, com um faturamento total de R$ 780.082,71, enquanto as outras três lojas faturaram, em média, R$ 1,27 milhão cada.

Pior Satisfação do Cliente: A Loja 3 possui a pior avaliação média, com 3.05 estrelas. Este é um indicador crítico, pois as outras três lojas mantêm uma média saudável acima de 4.0 estrelas.

Custo de Frete Proibitivo: O fator mais alarmante é o frete. A Loja 3 tem um custo médio de frete de R$ 34,99. Este valor é 73% mais caro que a média das outras lojas (R$ 20,26), o que impacta diretamente a taxa de conversão (levando a menos vendas) e a satisfação do cliente (levando a piores avaliações).

Curiosamente, a análise de Categorias mostrou que todas as lojas vendem os mesmos tipos de produtos (móveis, eletrônicos, brinquedos). Isso reforça que o problema da Loja 3 não é o produto, mas sim a operação logística e seus custos.

6. Como Executar
Faça o download do arquivo AluraStoreBrasil.ipynb.

Faça o upload do notebook para o seu Google Drive.

Abra o arquivo com o Google Colab.

No menu superior, clique em "Ambiente de execução" e depois em "Executar tudo".

O notebook irá baixar os dados, realizar as análises e gerar os gráficos e o relatório final.
