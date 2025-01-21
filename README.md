# Desafio-Projeto-Conceitual-de-Banco-de-Dados
Resolução do Desafio de Projeto Conceitual de Banco de Dados do bootcamp da DIO sobre desenvolvimento de Banco de Dado
## Contexto

Modelar um Banco de Dados relacional de um sistema de e-commerce baseado na seguinte descrição

### Produtos 
Produtos tem varios vendedores

Produtos tem varios fornecedores

Pedido é composto de um ou mais produtos

### Cliente e Pedido
Cliente é cadastrada com CPF ou CNPJ

Endereço determina valor do frete

Cliente pode comprar varios pedidos, cada pedido tem um carência para devolução

Pedido pode ser cancelado

Pedido são criados por cliente e possuem compra, endereço e status de entrega

## Desafio

Refinar o projeto para que :

- Cliente tenha CPF ou CNPJ, mas nunca as duas informações
- Pode ser cadastrado mais de uma forma de pagamento por cliente
- Entrega possui status e codigo de rastreio
