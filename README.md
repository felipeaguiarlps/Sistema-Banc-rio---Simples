# Sistema Bancário Simples

Este é um sistema bancário simples, implementado em Python, que permite operações básicas como depósito, saque, visualização de extrato, criação de usuários e contas, além de listar as contas registradas.

## Funcionalidades

- **Depósito**: Realiza depósitos na conta.
- **Saque**: Permite saques com controle de saldo e limite de transações diárias.
- **Extrato**: Exibe um extrato detalhado das movimentações da conta.
- **Criar Usuário**: Registra novos usuários no sistema.
- **Criar Conta**: Cria uma nova conta bancária associada a um usuário.
- **Listar Contas**: Lista todas as contas registradas no banco de dados.

## Como Executar

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git

## Exemplo de Uso

Ao executar o programa, o seguinte menu será exibido:
==================== Menu ===================
[d]    Depositar
[s]    Sacar
[e]    Extrato
[nc]   Nova conta
[lc]   Listar contas
[nu]   Novo usuário
[q]    Sair

###Depósito
Para realizar um depósito, selecione a opção d e informe o valor a ser depositado.

###Saque
Para realizar um saque, selecione a opção s, informe o valor, e o sistema verificará o saldo, o limite diário e o número de saques disponíveis.

###Extrato
Selecione a opção e para visualizar o extrato das movimentações e o saldo da conta.

###Criar Usuário
A opção nu permite registrar novos usuários no sistema.

###Criar Conta
Para criar uma nova conta associada a um usuário, selecione a opção nc.

###Listar Contas
Selecione a opção lc para listar todas as contas registradas no banco de dados.

###Requisitos
Python 3.x