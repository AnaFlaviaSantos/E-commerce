# E-commerce - Modelo Conceitual ER

Este projeto é um refinamento de modelo conceitual de banco de dados para um sistema de e-commerce, utilizando como ferramenta MySQL Workbench.

## 📌 Objetivo

Refinar o projeto inicial definindo os seguintes pontos abordados no desafio:
- O cliente pode ser Pessoa Física (PF) ou Pessoa Jurídica (PJ), mas não pode ser ambos simultaneamente.
- Um pedido pode ser pago utilizando mais de uma forma de pagamento.
- A entrega deve conter um código de rastreio e um status atualizado.

## 📝 Entidades

- Cliente (Pessoa Física ou Jurídica)
- Pedido
- Produto
- Fornecedor
- Estoque
- Vendedor Terceirizado
- Forma de Pagamento
- Entrega

## 🔗 Relacionamentos refinados

- Cliente (Pessoa Física ou Jurídica)
- Pagamento de Pedido
- Entrega de Pedido
