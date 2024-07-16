# Sistema Bancário Simples

Este é um projeto de um sistema bancário simples em Python que permite aos usuários realizar depósitos, saques, visualizar o extrato e sair do programa. O sistema possui um menu interativo e mantém o saldo e as transações do usuário.

## Funcionalidades

- **Depositar**: Permite ao usuário adicionar um valor ao saldo.
- **Sacar**: Permite ao usuário retirar um valor do saldo, respeitando o limite diário de saques e o limite de valor por saque.
- **Extrato**: Exibe todas as transações realizadas e o saldo atual.
- **Sair**: Encerra o programa.

## Limitações

- Limite de saque por transação: R$ 500,00
- Limite diário de saques: 3 saques
- Não é permitido realizar operações com valores negativos ou nulos

## Como Usar

1. Clone este repositório.
2. Abra o terminal e navegue até o diretório do projeto.
3. Execute o script Python:

```sh
python sistema_bancario.py
