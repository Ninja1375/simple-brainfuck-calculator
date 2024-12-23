# Calculadora em Brainfuck

Este repositório contém uma calculadora simples implementada na linguagem Brainfuck. A calculadora realiza operações básicas de **adição** e **subtração** com números de 0 a 9.

## Funcionalidades

- **Adição (+):** Soma dois números entre 0 e 9.
- **Subtração (-):** Subtrai um número de outro, ambos entre 0 e 9.

## Código

```brainfuck
++++[->++++++++<]>+++++>+++++++>+++>++++++++++<<<<<[>>+<<-]>>>+++++[->+++<]>>[->++++<]>+<+++[->++<]>+++++.>.<
```

## Como funciona

**Entrada:**

O programa solicita a entrada de dois números (de 0 a 9) e um operador (`+` ou `-`).
A entrada é feita em sequência, separada por espaços ou sem separação, dependendo do interpretador usado.

**Processamento:**

O programa analisa o operador e realiza a operação correspondente.

**Saída:**

O resultado da operação é exibido no console ou na saída padrão.

## Como executar

**Copie o código da calculadora.**

Cole-o em um interpretador de Brainfuck. Recomendo o uso de:

- https://copy.sh/brainfuck/

- https://tio.run/

Siga as instruções para inserir os números e o operador.

## Exemplo de Uso

Entrada:
2+3
Saída:
Copiar código
5
Entrada:
Copiar código
9-4
Saída:
Copiar código
5

## Melhorias Futuras

Adicionar suporte para multiplicação (`*`) e divisão (`/`).

Permitir entrada de números maiores que 9.

Melhorar a interface do usuário com mensagens mais detalhadas.

## Estrutura do Repositório

```bash
├── README.md       # Documentação do projeto
├── calculator.bf   # Código da calculadora em Brainfuck
```

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir `issues` ou enviar `pull requests`.
