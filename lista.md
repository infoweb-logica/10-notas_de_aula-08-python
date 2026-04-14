# Exercícios — Estruturas de Repetição com `while` em Python

> **Público alvo**: alunos da disciplina de Introdução a Lógica e Programação  
> **Objetivo**: praticar o uso de `while` para resolver problemas de programação  
> **Referência**: problemas inspirados na Olimpíada Brasileira de Informática (OBI) — modalidade Programação, níveis Júnior, 1, 2 e Sênior

---

## 🟢 Nível Fácil (Questões 1 a 15)

> Inspirado na OBI — Nível Júnior. Use `while` para resolver cada problema.

---

**Questão 1 — Contagem regressiva**

Leia um número inteiro positivo `N`. Imprima todos os números de `N` até `1` em ordem decrescente, um por linha. Ao final, imprima `Fogo!`.

*Exemplo:*
- Entrada: `5`
- Saída: `5 4 3 2 1 Fogo!`

---

**Questão 2 — Soma dos primeiros N inteiros**

Leia um número inteiro positivo `N`. Calcule e imprima a soma de todos os inteiros de `1` até `N`.

*Exemplo:*
- Entrada: `10`
- Saída: `55`

---

**Questão 3 — Tabuada**

Leia um número inteiro `N` (1 ≤ N ≤ 10). Imprima a tabuada de multiplicação de `N`, do 1 ao 10, no formato `N x i = resultado`.

*Exemplo (N=3):*
```
3 x 1 = 3
3 x 2 = 6
...
3 x 10 = 30
```

---

**Questão 4 — Fatorial**

Leia um número inteiro não-negativo `N`. Calcule e imprima o valor de `N!` (fatorial de N). Considere que `0! = 1`.

*Exemplo:*
- Entrada: `5`
- Saída: `120`

---

**Questão 5 — Média de notas**

Leia `N` notas de alunos (valores reais entre 0 e 10). Calcule e imprima a média aritmética com duas casas decimais.

*Exemplo (N=4, notas: 7.0, 8.5, 6.0, 9.5):*
- Saída: `7.75`

---

**Questão 6 — Soma até sentinela**

Leia números inteiros um por vez até que o usuário digite `0`. Imprima a soma de todos os números lidos (excluindo o zero).

*Exemplo (entrada: 3, 7, 2, -1, 0):*
- Saída: `11`

---

**Questão 7 — Contagem de pares e ímpares**

Leia `N` números inteiros. Conte quantos são pares e quantos são ímpares. Imprima os dois resultados.

*Exemplo (N=5, valores: 1, 2, 3, 4, 5):*
- Saída: `Pares: 2` / `Ímpares: 3`

---

**Questão 8 — Maior e menor valor**

Leia `N` números inteiros (N ≥ 1). Encontre e imprima o maior e o menor valor entre eles.

*Exemplo (N=4, valores: 3, 7, 1, 5):*
- Saída: `Maior: 7` / `Menor: 1`

---

**Questão 9 — Potências de 2**

Leia um número inteiro `N`. Imprima todas as potências de 2 menores ou iguais a `N`, começando por 1 (2⁰ = 1).

*Exemplo (N=100):*
- Saída: `1 2 4 8 16 32 64`

---

**Questão 10 — Sequência de Fibonacci**

Leia um número inteiro positivo `N`. Imprima os `N` primeiros termos da sequência de Fibonacci (começando por 0 e 1).

*Exemplo (N=7):*
- Saída: `0 1 1 2 3 5 8`

---

**Questão 11 — Soma dos dígitos**

Leia um número inteiro positivo `N`. Calcule e imprima a soma dos dígitos que compõem `N`.

*Exemplo:*
- Entrada: `1234`
- Saída: `10`

---

**Questão 12 — Inversão de número**

Leia um número inteiro positivo `N`. Imprima o número com seus dígitos na ordem inversa.

*Exemplo:*
- Entrada: `1234`
- Saída: `4321`

---

**Questão 13 — Contagem de dígitos**

Leia um número inteiro positivo `N`. Imprima quantos dígitos ele possui.

*Exemplo:*
- Entrada: `9087`
- Saída: `4`

---

**Questão 14 — Número primo**

Leia um número inteiro `N` (N ≥ 2). Determine se ele é primo ou não. Imprima `Primo` ou `Não primo`.

*Exemplo:*
- Entrada: `17`
- Saída: `Primo`

---

**Questão 15 — Múltiplos de K**

Leia dois inteiros `N` e `K`. Imprima todos os múltiplos de `K` no intervalo de `1` a `N`, um por linha.

*Exemplo (N=20, K=3):*
- Saída: `3 6 9 12 15 18`

---

## 🟡 Nível Médio (Questões 16 a 35)

> Inspirado na OBI — Nível 1 e Nível 2. Problemas envolvem lógica mais elaborada, sequências e acumuladores compostos.

---

**Questão 16 — Sequência de Collatz**

Dado um número inteiro positivo `N`, aplique a seguinte regra repetidamente até chegar em 1: se `N` for par, divida por 2; se for ímpar, multiplique por 3 e some 1. Imprima cada valor da sequência (incluindo o inicial e o 1 final) e o número total de passos.

*Exemplo (N=6):*
- Sequência: `6 3 10 5 16 8 4 2 1`
- Passos: `8`

---

**Questão 17 — Máximo divisor comum (MDC)**

Leia dois inteiros positivos `A` e `B`. Use o algoritmo de Euclides com `while` para calcular e imprimir o MDC de `A` e `B`.

*Exemplo:*
- Entrada: `48 18`
- Saída: `6`

---

**Questão 18 — Mínimo múltiplo comum (MMC)**

Leia dois inteiros positivos `A` e `B`. Calcule e imprima o MMC de `A` e `B` usando `while` (sem usar a fórmula direta com MDC).

*Exemplo:*
- Entrada: `4 6`
- Saída: `12`

---

**Questão 19 — Conversão de base: decimal para binário**

Leia um número inteiro não-negativo `N`. Converta-o para a representação binária usando divisões sucessivas por 2. Imprima o resultado binário como uma string.

*Exemplo:*
- Entrada: `13`
- Saída: `1101`

---

**Questão 20 — Número perfeito**

Um número inteiro positivo é perfeito se a soma de seus divisores próprios (excluindo ele mesmo) for igual a ele. Leia `N` inteiros positivos e, para cada um, informe se é perfeito ou não.

*Exemplo:*
- Entrada: `6` → Saída: `Perfeito` (1+2+3=6)
- Entrada: `10` → Saída: `Não perfeito`

---

**Questão 21 — Número de Armstrong**

Um número de `n` dígitos é de Armstrong (ou narcisista) se a soma de seus dígitos elevados à `n`-ésima potência for igual ao próprio número. Leia `N` inteiros e informe se cada um é ou não de Armstrong.

*Exemplo:*
- Entrada: `153` → Saída: `Armstrong` (1³ + 5³ + 3³ = 153)
- Entrada: `100` → Saída: `Não Armstrong`

---

**Questão 22 — Palíndromo numérico**

Leia um número inteiro positivo `N`. Usando apenas operações aritméticas com `while`, determine se `N` é um palíndromo (lê-se igual de frente para trás).

*Exemplo:*
- Entrada: `1221` → Saída: `Palíndromo`
- Entrada: `1234` → Saída: `Não palíndromo`

---

**Questão 23 — Série harmônica**

Leia um número real `X` (X > 0). Calcule quantos termos da série harmônica `H = 1 + 1/2 + 1/3 + ... + 1/n` são necessários para que `H` supere `X`. Imprima o número de termos.

*Exemplo:*
- Entrada: `2.0`
- Saída: `4` (1 + 0.5 + 0.333... + 0.25 = 2.083...)

---

**Questão 24 — Raiz inteira**

Leia um inteiro não-negativo `N`. Sem usar funções de raiz quadrada, encontre o maior inteiro `k` tal que `k² ≤ N`. Imprima `k`.

*Exemplo:*
- Entrada: `26`
- Saída: `5` (5² = 25 ≤ 26 < 36 = 6²)

---

**Questão 25 — Sequência até superar limite**

Considere a sequência definida por: `a(1) = 1`, `a(n) = a(n-1) + 2*n - 1`. Leia um inteiro `L`. Encontre o menor `n` tal que `a(n) > L`. Imprima `n` e `a(n)`.

*Exemplo (L=20):*
- Saída: `n=5, a(5)=25`

---

**Questão 26 — Contagem de divisores**

Leia um inteiro positivo `N`. Conte e imprima o número de divisores positivos de `N` (incluindo 1 e N).

*Exemplo:*
- Entrada: `12`
- Saída: `6` (divisores: 1, 2, 3, 4, 6, 12)

---

**Questão 27 — Soma dos números primos até N**

Leia um inteiro positivo `N`. Calcule e imprima a soma de todos os primos menores ou iguais a `N`.

*Exemplo (N=10):*
- Saída: `17` (2+3+5+7)

---

**Questão 28 — Número digital persistente**

A persistência multiplicativa de um número é o número de vezes que se deve multiplicar seus dígitos até obter um único dígito. Leia `N` e calcule sua persistência multiplicativa.

*Exemplo:*
- Entrada: `39` → 3×9=27 → 2×7=14 → 1×4=4 → Persistência: `3`

---

**Questão 29 — Sequência de soma acumulada com filtro**

Leia inteiros um por vez até que a soma acumulada supere 1000. Considere apenas os valores positivos para a soma. Imprima quantos números foram lidos no total e quantos eram positivos.

*Exemplo (entrada: 200, -50, 300, 600):*
- Saída: `Total lidos: 4` / `Positivos: 3`

---

**Questão 30 — Critério de Gauss: soma de PA**

Em uma progressão aritmética (PA), a soma dos `N` primeiros termos é `S = N*(a1 + aN)/2`. Leia os valores `a1` (primeiro termo), `r` (razão) e `S_max` (soma máxima desejada). Usando `while`, some os termos da PA um a um até que a soma ultrapasse `S_max` ou atinja 1000 termos. Imprima quantos termos foram somados e a soma final.

---

**Questão 31 — Número de passos para zero (raiz digital)**

A raiz digital de um número é obtida somando repetidamente seus dígitos até restar um único dígito. Leia `N` e imprima a raiz digital e o número de iterações necessárias.

*Exemplo:*
- Entrada: `9875` → 9+8+7+5=29 → 2+9=11 → 1+1=2 → Raiz: `2`, Iterações: `3`

---

**Questão 32 — Crivo simplificado: primos em um intervalo**

Leia dois inteiros `A` e `B` (A ≤ B). Imprima todos os números primos no intervalo `[A, B]`, um por linha. Ao final, informe a quantidade total de primos encontrados.

---

**Questão 33 — Sequência de Padovan**

A sequência de Padovan é definida por: `P(0)=P(1)=P(2)=1` e `P(n) = P(n-2) + P(n-3)`. Leia `N` e imprima os `N` primeiros termos.

*Exemplo (N=8):*
- Saída: `1 1 1 2 2 3 4 5`

---

**Questão 34 — Exponenciação modular**

Leia três inteiros `B`, `E` e `M`. Calcule `B^E mod M` usando o método de exponenciação por quadratura iterativa com `while` (sem usar `pow(B, E, M)`). Imprima o resultado.

*Exemplo:*
- Entrada: `2 10 1000`
- Saída: `24`

---

**Questão 35 — Maior primo fator**

Leia um inteiro positivo `N` (N ≥ 2). Encontre e imprima o maior fator primo de `N`.

*Exemplo:*
- Entrada: `84`
- Saída: `7` (84 = 2² × 3 × 7)

---

## 🔴 Nível Difícil (Questões 36 a 50)

> Inspirado na OBI — Nível 2 e Sênior. Problemas exigem raciocínio algorítmico avançado, simulações e técnicas clássicas de olimpíadas.

---

**Questão 36 — Simulação de jogo: pedra, papel e tesoura**

Dois jogadores disputam uma partida de pedra, papel e tesoura ao melhor de `N` rodadas (vence quem ganhar mais rodadas). Leia `N` e, em seguida, as jogadas de cada rodada como pares de caracteres (`P`=pedra, `T`=tesoura, `S`=papel/scissors). Use `while` para processar as rodadas e imprimir o resultado de cada uma e o placar final. Informe o vencedor ou empate.

---

**Questão 37 — Subsequência crescente máxima (comprimento)**

Leia `N` inteiros. Usando apenas `while` e variáveis auxiliares (sem listas), determine o comprimento da maior subsequência crescente **contígua** (subarray crescente consecutivo).

*Exemplo (N=8, valores: 1 2 3 1 2 3 4 5):*
- Saída: `5` (1 2 3 4 5)

---

**Questão 38 — Problema do troco mínimo (algoritmo guloso)**

Leia um valor inteiro `V` (em centavos) e as denominações disponíveis: 100, 50, 25, 10, 5, 1. Usando `while` para cada denominação, calcule o número mínimo de moedas necessárias para dar o troco. Imprima quantas moedas de cada denominação são usadas.

---

**Questão 39 — Sequência de Rudin–Shapiro**

A sequência de Rudin–Shapiro é definida pelo número de pares `11` (consecutivos) na representação binária de `n`. Se esse número for par, `r(n)=1`; se ímpar, `r(n)=-1`. Leia `N` e imprima os primeiros `N` termos da sequência.

*Exemplo (N=8):*
- Saída: `1 1 1 -1 1 1 -1 1`

---

**Questão 40 — Detector de ciclo em sequência (Floyd)**

Leia uma sequência de inteiros terminada por `-1`. Usando o algoritmo de Floyd (tartaruga e lebre) simulado com `while` sobre os índices da sequência armazenada, detecte se existe um ciclo. Imprima `Tem ciclo` ou `Sem ciclo` e, se houver ciclo, o comprimento dele.

> Dica: armazene a sequência e simule os ponteiros sobre os índices.

---

**Questão 41 — Jogo de Nim (estratégia vencedora)**

No jogo de Nim, há `K` pilhas com quantidades de pedras. Dois jogadores alternam retirando qualquer quantidade de pedras de uma única pilha. Perde quem retirar a última pedra. Leia `K` e as quantidades de cada pilha. Usando `while` para simular o XOR das pilhas, determine se o primeiro jogador tem estratégia vencedora e imprima `Vence` ou `Perde`.

---

**Questão 42 — Maior palíndromo produto de dois números de N dígitos**

Leia um inteiro `N` (1 ≤ N ≤ 3). Encontre o maior número palíndromo que seja produto de dois números com exatamente `N` dígitos. Use `while` aninhado para iterar pelos candidatos. Imprima o palíndromo e os dois fatores.

*Exemplo (N=2):*
- Saída: `9009 = 91 x 99`

---

**Questão 43 — Contagem de caminhos em grade (sem recursão)**

Considere uma grade `M × N`. Você começa no canto superior esquerdo e pode apenas se mover para a direita ou para baixo. Leia `M` e `N`. Usando `while` para simular o preenchimento de uma tabela de programação dinâmica, calcule e imprima o número de caminhos distintos até o canto inferior direito.

*Exemplo (M=3, N=3):*
- Saída: `6`

---

**Questão 44 — Fração de Stern–Brocot**

A árvore de Stern–Brocot gera todas as frações positivas irredutíveis. Leia dois inteiros `P` e `Q` (0 < P/Q < 1, P e Q coprimos). Usando `while`, encontre a sequência de movimentos (L=esquerda, R=direita) para localizar P/Q na árvore de Stern–Brocot. Imprima a sequência de movimentos e a profundidade.

---

**Questão 45 — Simulação de fila (queue) com atendimento**

Um caixa atende clientes em fila. Leia `N` eventos no formato `C X` (chegada do cliente X) ou `A` (atendimento, remove o próximo da fila). Simule a fila com `while` e, ao final, imprima a ordem em que os clientes foram atendidos e quantos ainda aguardam.

---

**Questão 46 — Número de partições de N (sem recursão)**

Leia um inteiro `N` (1 ≤ N ≤ 50). Usando programação dinâmica iterativa com `while`, calcule e imprima o número de maneiras de representar `N` como soma de inteiros positivos (partições de N), onde a ordem não importa.

*Exemplo (N=4):*
- Saída: `5` (4; 3+1; 2+2; 2+1+1; 1+1+1+1)

---

**Questão 47 — Menor número com K divisores**

Leia um inteiro `K`. Encontre e imprima o menor inteiro positivo que possui exatamente `K` divisores.

*Exemplo (K=6):*
- Saída: `12` (divisores: 1, 2, 3, 4, 6, 12)

---

**Questão 48 — Simulação de autômato celular (Regra 110)**

O autômato celular da Regra 110 opera sobre uma linha de células binárias. A cada geração, o novo estado de cada célula depende dela e de suas vizinhas segundo a Regra 110. Leia o estado inicial como uma string de `0`s e `1`s e um inteiro `G` (número de gerações). Usando `while`, imprima o estado após cada geração.

---

**Questão 49 — Problema da mochila 0/1 (programação dinâmica)**

Você tem uma mochila com capacidade `W` e `N` itens, cada um com peso `w_i` e valor `v_i`. Usando programação dinâmica iterativa com `while`, calcule o valor máximo que pode ser colocado na mochila sem ultrapassar a capacidade. Imprima o valor máximo.

*Restrições: N ≤ 20, W ≤ 1000.*

---

**Questão 50 — Menor caminho em grafo (Dijkstra iterativo)**

Leia um grafo com `V` vértices e `E` arestas dirigidas com pesos positivos. Em seguida, leia o vértice de origem `S`. Usando `while` para implementar o algoritmo de Dijkstra com seleção manual do menor custo (sem fila de prioridade), calcule e imprima a distância mínima de `S` a todos os outros vértices. Use `INF` para vértices inacessíveis.

*Restrições: V ≤ 100, E ≤ 500.*

---

## 📊 Resumo

| Nível   | Questões | Referência OBI         |
|---------|----------|------------------------|
| Fácil   | 1 – 15   | Júnior                 |
| Médio   | 16 – 35  | Nível 1 e Nível 2      |
| Difícil | 36 – 50  | Nível 2 e Sênior       |
| **Total** | **50** |                        |
