# Sistema de Pedidos

Este projeto em Java simula um sistema de pedidos simples, onde é possível cadastrar um cliente, criar um pedido com status, adicionar itens ao pedido e exibir as informações detalhadas do pedido, incluindo os itens e o valor total.

## Funcionalidades

- Cadastro de cliente (nome, email e data de nascimento).
- Criação de pedido com status (PENDING_PAYMENT, PROCESSING, SHIPPED, DELIVERED).
- Adição de itens ao pedido (produto, preço, quantidade).
- Cálculo automático do preço total do pedido.
- Exibição de todas as informações do pedido de forma formatada.

## Estrutura do Projeto

O projeto possui as seguintes entidades:

- **Client**: Representa o cliente, com nome, email e data de nascimento.
- **Order**: Representa um pedido, contendo a data, status, cliente e lista de itens.
- **OrderItem**: Representa um item dentro de um pedido, incluindo quantidade, preço e produto.
- **Product**: Representa um produto com nome e preço.
- **OrderStatus**: Enumeração para representar o status do pedido.
