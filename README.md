# README.md — Sistema de caixa eletrônico (ATM simplificado)

## Descrição

Este repositório contém a resolução da **Atividade 01** da disciplina **Algoritmos e Pensamento Computacional**, ministrada pelo professor **Francisco de Assis Cavallaro**.

O projeto consiste na implementação de um **Sistema de Caixa Eletrônico (ATM) Simplificado** em linguagem **C**, cujo objetivo é simular a operação de saque em um caixa eletrônico, realizando a verificação de regras de negócio e o cálculo da distribuição de cédulas.

---

## Finalidade

Desenvolver o raciocínio lógico e computacional por meio da construção de um algoritmo capaz de:

1. Solicitar ao usuário o valor que deseja sacar;
2. Verificar se o valor informado é **múltiplo de 5** e **menor ou igual ao saldo disponível**;
3. Calcular a **quantidade de notas** a serem entregues, considerando as cédulas de **100, 50, 20, 10 e 5**;
4. Exibir a **distribuição das notas** entregues ao usuário;
5. Apresentar **mensagens de erro apropriadas** caso o saque não seja possível.

---

## Regras de negócio

| Regra | Descrição |
|-------|-----------|
| **R1** | O valor do saque deve ser **múltiplo de 5** |
| **R2** | O valor do saque deve ser **menor ou igual ao saldo disponível** |
| **R3** | As notas disponíveis para saque são: **100, 50, 20, 10 e 5** |
| **R4** | A distribuição deve priorizar as notas de maior valor (greedy) |
| **R5** | Em caso de falha em R1 ou R2, exibir mensagem de erro apropriada |

---

## 🧪 Exemplo de execução

```text
Digite o valor do saque: 285

Notas entregues:
2 nota(s) de 100
1 nota(s) de 50
1 nota(s) de 20
1 nota(s) de 10
1 nota(s) de 5
