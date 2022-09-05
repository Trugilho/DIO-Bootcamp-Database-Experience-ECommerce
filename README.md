# DIO-Bootcamp-Database-Experience-ECommerce

Construindo seu primeiro projeto de Banco de dados - 
Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE - 

Descrição do Desafio
O esquema adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicionado ao Readme a descrição do projeto conceitual para fornecer o contexto sobre seu esquema.

Objetivo:
Refinado o modelo apresentado acrescentando os seguintes pontos:

Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
Entrega – Possui status e código de rastreio;

Projeto Conceitual Banco Dados ECommerce
Narrativa: Escopo de E-Commerce - Venda de produtos.
Entidades:
Cliente
Pagamentos
Pedido
Entrega
Vendedor Parceiro
Produtos
Estoque
Fornecedor

Produto - Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos(Vendedor parceiro).
Cada produto possui um fornecedor.
Um ou mais produtos podem compor um pedido.

Cliente - O cliente pode se cadastrar no site com seu CPF ou CNPJ. O endereço do cliente irá determinar o valor do frete.
Um cliente pode compar mais de um pedido. Este tem um período de carência par devolução do produto.

Pontos de refinamento:
Forma de pgto em Cliente(cartões) - Podem ser cadastradas mais de uma forma de pgto, necessário ter os dados do cartão(número id) menos o código secreto.
Entrega Vale a pena ter uma nova entidade ou um atributo do pedido? Possui status e código de rastreio(atreladas ao pedido a uma nova entidade?).
Cliente pode ser PF e PJ - Uma conta pode ser PF ou PJ, mas não pode ter as duas informações.

Pedido -  Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega.
Um produto ou mais compõem o pedido.
O pedido pode ser cancelado.
