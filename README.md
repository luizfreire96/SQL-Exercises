# SQL-Exercicios
## Banco de dados disponível em: 
# https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

### Exercícios referentes ao curso intensivo de data science da Awari

# Desafio 1:
## Query 1:
### Retorna os pagamentos realizados por boleto ou voucher

## Query 2:
### Retorna o volume dos produtos em um novo campo

## Query 3:
### Retorna as reviews que não possuem comentários

## Query 4: 
### Retorna os pedidos feitos em 2017

## Query 5:
### Retorna os pedidos das cidades de São Paulo que não sejam a capital

# Desafio 2:
## Query 1:
### retorna a quantidade de itens vendidos em cada categoria por estado em que o cliente se encontra, mostrando somente categorias que tenham vendido uma quantidade de items acima de 1000.

## Query 2: 
### Retorna os 5 clientes (customer_id) que gastaram mais dinheiro em compras, qual foi o valor total de todas as compras deles, quantidade de compras, e valor médio gasto por compras. Ordene os mesmos por ordem decrescente pela média do valor de compra.

## Query 3:
### Retorna o valor vendido total de cada vendedor (seller_id) em cada uma das categorias de produtos, somente retornando os vendedores que nesse somatório e agrupamento venderam mais de $1000. Desejamos ver a categoria do produto e os vendedores. Para cada uma dessas categorias, mostre seus valores de venda de forma decrescente.

# Desafio 3:
## Query 1:
### Cria uma tabela analítica de todos os itens que foram vendidos, mostrando somente pedidos interestaduais. Queremos saber quantos dias os fornecedores demoram para postar o produto, se o produto chegou ou não no prazo.

## Query 2:
### Retorna todos os pagamentos do cliente, com suas datas de aprovação, valor da compra e o valor total que o cliente já gastou em todas as suas compras, mostrando somente os clientes onde o valor da compra é diferente do valor total já gasto.

## Query 3:
### Retorna as categorias válidas, suas somas totais dos valores de vendas, um ranqueamento de maior valor para menor valor junto com o somatório acumulado dos valores pela mesma regra do ranqueamento. É possivel observar também um evento que segue aproximadamente do principio de pareto

# Desafio 4:
## Query 1:
### Cria uma view (SELLER_STATS) para mostrar por fornecedor, a quantidade de itens enviados, o tempo médio de postagem após a aprovação da compra, a quantidade total de pedidos de cada Fornecedor, note que trabalharemos na mesma query com 2 granularidades diferentes.

## Query 2:
### Queremos dar um cupom de 10% do valor da última compra do cliente. Porém os clientes elegíveis a este cupom devem ter feito uma compra anterior a última (a partir da data de aprovação do pedido) que tenha sido maior ou igual o valor da última compra. Crie uma querie que retorne os valores dos cupons para cada um dos clientes elegíveis.
