# Abaixo você encontra explicação sobre o diagrama referente a atividade (Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE)

## As entidades principais do sistema são:

## Produto
* Os produtos são vendidos exclusivamente pela plataforma online.
* Os produtos podem ter vendedores distintos, incluindo terceiros.
* Cada produto é associado a um fornecedor específico.
* Um ou mais produtos podem compor um pedido.

## Cliente
* Os clientes podem se cadastrar no site utilizando seu CPF ou CNPJ.
* O endereço do cliente é utilizado para determinar o valor do frete.
* Um cliente pode realizar mais de um pedido.
* Os clientes possuem um período de carência para a devolução do produto, de acordo com as políticas da plataforma.
## Pedido
* Os pedidos são criados pelos clientes.
Cada pedido contém informações de compra, como os produtos selecionados.
* Os pedidos incluem também informações de endereço e status de entrega.
* Um pedido pode ser composto por um ou mais produtos.
* Existe a opção de cancelamento de um pedido.
## Fornecedor
* Um fornecedor é associado a cada produto.
* O fornecedor possui um CPF ou CNPJ.
* Cada fornecedor possui uma razão social.
## Estoque
* É necessário informar a quantidade de produtos disponíveis em estoque.
* É possível registrar o local onde o estoque está armazenado para facilitar o gerenciamento.
