# Sistema Bancário Simples em Python
**Autor**: Renato Mesquita

**Data**: 14/07/2024

Este é um sistema bancário básico implementado em Python, que permite realizar operações como depósito, saque, exibição de extrato e saída do programa.

## Funcionalidades

- **Depositar**: Adiciona um valor ao saldo da conta.
- **Sacar**: Permite retirar dinheiro da conta, respeitando um limite máximo por saque e um limite diário de saques.
- **Extrato**: Mostra todas as transações realizadas na conta e o saldo atual.
- **Sair**: Encerra o programa.

## Como usar

1. **Execução**:
   - Certifique-se de ter Python instalado no seu sistema.
   - Clone este repositório ou baixe o arquivo `banco.py`.
   - Abra um terminal ou prompt de comando na pasta onde está o arquivo `banco.py`.

2. **Execução do programa**:
   - Digite `python banco.py` e pressione Enter.
   - Siga as instruções exibidas no console para realizar operações bancárias.

3. **Operações disponíveis**:
   - Siga o menu apresentado para selecionar a operação desejada.
   - Digite as informações solicitadas, como valor de depósito ou saque.



## Tecnologias

- Python 3 (básico)


## Objetivo

O objetivo desse desafio é criar um sistema bancário com as operações: sacar, depositar e visualizar extrato.


## Proposta

Fomos contratados por um grande banco para desenvolver seu novo sistema. Esse banco deseja modernizar suas operações e, para isso, escolheu a linguagem Python. 

Para a primeira versão do sistema, devemos implementar apenas 3 operações: depósito, saque e extrato.

### Operação de depósito
Deve ser possível depositar valores positivos para uma conta bancária. A v1 do projeto trabalha com apenas 1 usuário, então não é necessário se preocupar com a identificação do número da agência e nem da conta bancária.

Todos os depósitos devem ser armazenados numa variável e exibidos na operação de extrato.

### Operação de saque
O sistema deve permitir realizar 3 saques diários com limite máximo de R$500,00/saque. Caso o usuário não tenha saldo em conta, o sistema deve exibir uma mensagem informando que não será possível sacar dinheiro por falta de saldo.

Todos os saques devem ser armazenados numa variável e exibidos na operação de extrato.

### Operação de extrato
Deve listar todos os depósitos e saques realizados na conta. No fim da lista, deve ser exibido o saldo atual da conta.

Os valores devem ser exibidos utilizando o formato R$ xxx.xx.