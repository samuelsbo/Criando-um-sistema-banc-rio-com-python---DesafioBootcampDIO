# Projeto de Sistema Bancário com Python

Bem-vindo ao **Sistema Bancário com Python**, um projeto desenvolvido para simular operações básicas de um sistema bancário utilizando a linguagem de programação Python.

## Sumário

- [Descrição](#descrição)
- [Funcionalidades](#funcionalidades)
  - [Menu Inicial](#menu-inicial)
  - [Depósito](#depósito)
  - [Saque](#saque)
  - [Extrato](#extrato)
- [Autor](#autor)

## Descrição

O **Sistema Bancário com Python** é uma aplicação de console que permite aos usuários realizar operações bancárias básicas, tais como depósitos, saques e visualização de extratos. O sistema é dividido em quatro partes principais, proporcionando uma experiência simples e intuitiva para o usuário.

## Funcionalidades

### Menu Inicial

O **Menu Inicial** é a interface principal do sistema, onde o usuário pode selecionar a operação desejada. As opções disponíveis são:

- **Depósito**: Permite ao usuário adicionar fundos à sua conta.
- **Saque**: Permite ao usuário retirar fundos da sua conta, com restrições aplicáveis.
- **Extrato**: Exibe o histórico de transações realizadas na conta.
- **Sair**: Encerra o sistema.

O menu é apresentado de forma clara e aguarda a entrada do usuário para prosseguir com a operação escolhida.

### Depósito

A funcionalidade de **Depósito** permite que o usuário adicione um valor positivo ao saldo da conta. O sistema valida se o valor informado é positivo antes de realizar a operação. Caso o valor seja inválido (não positivo), a operação é cancelada e uma mensagem de erro é exibida.

### Saque

A funcionalidade de **Saque** permite que o usuário retire fundos da sua conta, obedecendo às seguintes restrições:

- **Saldo Insuficiente**: O valor do saque não pode exceder o saldo disponível.
- **Limite de Saque**: Há um limite máximo por saque (R$ 500,00).
- **Número de Saques**: O usuário pode realizar no máximo 3 saques por dia.

Se alguma dessas condições não for atendida, o sistema informa o motivo da falha na operação.

### Extrato

A funcionalidade de **Extrato** exibe o histórico de todas as transações realizadas pelo usuário, incluindo depósitos e saques. Além disso, mostra o saldo atual da conta. Se nenhuma movimentação tiver sido realizada, o sistema informa que não há movimentações para exibir.

## Autor

Este projeto foi desenvolvido por Samuel Batista, baseado nas orientações do tutor Guilherme Arthur de Carvalho (@decarvalhogui). Sinta-se à vontade para entrar em contato ou contribuir com melhorias!
