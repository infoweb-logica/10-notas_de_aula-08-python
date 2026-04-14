# Notas de aula de 2026.1.10 - Python 08

## Informações gerais

- **Público alvo**: alunos da disciplina de **Introdução a lógica e programação** do curso de [Infoweb](https://diatinf.ifrn.edu.br/cursos/tecnico-em-informatica-para-internet/) na [DIATINF](https://diatinf.ifrn.edu.br/) no [CNAT-IFRN](https://portal.ifrn.edu.br/campus/natalcentral/)
- **Professor**: [L A Minora](https://github.com/leonardo-minora/)
- **Objetivo**:
  1. Mostrar o uso da instrução `while` para acumular valores

---
## Notas de aula [slides pdf](/08-Estrutura_de_repetição-while-acumular.pdf)
1. instrução while, é comum utilizarmos uma variável que atua como **contador** da quantidade de repetições. (Código contador abaixo)
2. Uma variável **acumuladora** é uma variável que é utilizada para acumular uma série de valores.

**Código contador**
```python
contador = 1
while contador <= 4:
  print(contador)
  contador = contador + 1
print("Fim")

```

**Código acumulador**
```python
contador = 1
acumulador = 0
while contador <= 4:
  print(contador)
  contador = contador + 1
  acumulador = acumulador + soma
print(f"total acumulado {acumulador}")
print("Fim")

```

---
## Exercícios [Lista de exercícios](/lista.md)
1. Escreva um programa que usa uma estrutura de repetição para calcular e imprimir a soma dos números inteiros compreendidos no intervalo [1; 10].

2. Escreva um programa que usa uma estrutura de repetição para calcular e imprimir a soma dos números inteiros compreendidos no intervalo [5; 10].

3. Escreva um programa que usa uma estrutura de repetição para calcular e imprimir a soma dos números pares compreendidos no intervalo [1; 10].

4. Escreva um programa que usa uma estrutura de repetição para calcular e imprimir imprime o produtório dos números inteiros compreendidos no intervalo [1; 4].

5. Escreva um programa que usa uma estrutura de repetição para calcular e imprimir o produtório dos números ímpares compreendidos no intervalo [1; 8].

6. Escreva um programa que tem como entrada um número inteiro positivo n e imprime a soma dos números inteiros de 1 a n.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 3                  | 6              |
| 10                 | 55             |
| 1                  | 1              |

7. Escreva um programa que tem como entrada um número inteiro positivo n e imprime o produtório dos números inteiros de 1 a n.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 3                  | 6              |
| 5                  | 120            |
| 1                  | 1              |

8. Escreva um programa que tem como entrada um número inteiro positivo n e imprime a soma dos múltiplos de 3 compreendidos entre 1 e n.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 7                  | 9              |
| 15                 | 45             |
| 2                  | 0              |

9. Escreva um programa que tem como entrada um número inteiro n ≥ 0 e que imprime o resultado da soma dada pela expressão 20 + 21 + 22 + … + 2n

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 0                  | 1              |
| 1                  | 3              |
| 2                  | 7              |
| 3                  | 15             |

10. Escreva um programa que tem como entrada um número inteito `contador` no intervalo [1; 10]. Quando o valor de `contador` estiver fora do intervalo, o programa deve informar que o número é inválido.
O valor de `contador` vai indicar quantos números serão informados e somados a variável `resultado_da_soma`.

| Exemplo de entrada | Saída esperada |
| ------------------ | -------------- |
| 0                  | Valor inválido |
| -1                 | Valor inválido |
| 11                 | Valor inválido |
| 1<br />número 1: 10 | Resultado da soma = 10 |
| 2<br />número 1: 10<br />número 2: 1 | Resultado da soma = 11 |
| 4<br />número 1: 10<br />número 2: 1<br />número 3: 5<br />número 4: 2 | Resultado da soma = 16 |
