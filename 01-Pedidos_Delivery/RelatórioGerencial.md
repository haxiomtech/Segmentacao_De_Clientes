# Relatório Gerencial

### Problema de Negócio: 

Agrupar os clientes com base nas ordens de pedido com o intuito de melhorar o sistema de promoções (Marketing).

- Segmentação 01 - Análise entre os produtos: Pizza e Sobremesa
- Segmentação 02 - Análise entre os produtos: Pizza e Salada
- Segmentação 03 - Análise entre os produtos: Pizza e Localidade

### Segmentação 01

Resultado obtido após análises, transformações dos dados e testes estatísticos.

![image](https://user-images.githubusercontent.com/119424591/206945940-b95fec20-2fb2-4cd5-b74b-12552cf16ece.png)

#### Interpretação

- O ponto vermelho é o centróide de cada cluster (segmento).

- No cluster 1 (área em verde) temos os clientes que pediram 0, 1 ou 2 Pizzas. Em todos os casos houve pedido de Sobremesa.

- No cluster 2 (área em cinza) estão clientes que pediram 2, 3, 4 ou 5 Pizzas. Perceba que à medida que o pedido tem maior número de Pizzas, também aumenta o número de Sobremesas.

#### Análise

Cluster 1 - Clientes que pedem menos Pizzas. Todos pedem sobremesa.

Cluster 2 - Clientes que pedem mais Pizzas. Todos pedem sobremesa em volume maior.

### Solução

#### Como estratégia de Marketing, poderíamos oferecer ao cliente uma sobremesa grátis no caso de comprar mais uma Pizza de maior valor. Com base na Segmentação provavelmente essa estratégia teria sucesso.


### Segmentação 02

Resultado obtido após análises, transformações dos dados e testes estatísticos.

![image](https://user-images.githubusercontent.com/119424591/206947376-2997e4b8-9320-446a-96da-2e7b26a0e908.png)

### Interpretação

O ponto vermelho é o centróide de cada cluster (segmento).

- No cluster 1 (área em cinza) temos os clientes que pediram menos Pizzas e mais Saladas.
- No cluster 2 (área em verde escuro) temos os clientes que pediram poucas Pizzas e poucas Saladas.
- No cluster 3 (área em verde claro) estão clientes que pediram mais Pizzas e menos Saladas.

### Análise e Solução

Os clusters 1 e 3 são de clientes com comportamentos opostos. A equipe de Marketing poderia concentrar os esforços nos clientes do cluster 2, pois são clientes que compram Pizzas e Saladas e, portanto, tendem a consumir mais itens variados evitando manter os estoques cheios de um único item.

Ou então, concentrar os esforços nos clientes que consomem produtos que geram mais lucro. Teríamos que verificar qual item, Pizza ou Salada, é mais rentável.

### Segmentação 03

Resultado obtido após análises, transformações dos dados e testes estatísticos.

![image](https://user-images.githubusercontent.com/119424591/206946935-ab9e8034-5090-4b6e-9c19-730fd929f218.png)

### Interpretação

- O ponto vermelho é o centróide de cada cluster (segmento).
- Observe que os clusters da esquerda no gráfico contém os pedidos de todas as Localidades, mas com menor número de Pizzas. Já os clusters da direita no gráfico contém pedidos de todas as Localidades com com maior número de Pizzas.

### Análise e Solução

Queremos aumentar as vendas, certo? Então teríamos que investigar mais a fundo os pedidos dos clusters à esquerda do gráfico e compreender em mais detalhes as características desses pedidos e que tipo de oferta podemos fazer.

Execução e Análise : A. Damasceno
