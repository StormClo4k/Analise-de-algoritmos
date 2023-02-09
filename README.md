# Analise de algoritmos - AULA1#
## Principio de indução matemática(Fraca)

A prova de uma afirmação por indução matemática feita em dois passos:

- 1 Passo base: 
- --
## 2 principio de indução matemática (Forte)

Seja P(n) um predicado que é definido para o inteiro n, e seja a e b inteiros fixos, a ≥ b.
A prova de P(n ) consiste em verificar a veracidade das seguintes afirmações:

- P(A), P(A +1) ..., P(B) são verdades (Passo base).
- Para qualquer K ≥ B se P(I) é verdade para k > i ≥ a , então P(k) é verdade (Passo indutivo).
---

## Corretude de algoritmos iterativos
invariantes :

- 1 Inicialização: mostre que o invariante vale no inicio da primeira interação
- 2 Manutenção: Suponha que o invariante vale no inicio de uma interação qualquer e prove que ele vale no inicio da próxima interação.
- 3 Termino: Conclua se o algoritmo para e o invariante vale no inicio da ultima interação, então o algoritmo está correto.
- A primeira e segunda implicação das invariantes vale para o inicio de qualquer interação do algoritmo, isso corresponde ao método de indução matemática.
---

## Laços aninhados

- Analisar um laço por vez começando pelo mais interno.
- bota na pipokinha
- de 4 da um tesao do krl
---

## Análise do algoritmo: Insertion sort

Ordena os valores da esquerda pra direita

| Column1 | Column2             | Column3              | Column4                  |
|--------:|----------------------------|:--------------------:|:------------------|
|         |                            |                      |                   |
| 50        |     44               |   13                   |ANTES   |
|         |                            |                      |                   |
|    13     |                   44         | 50|DEPOIS|

---
## Corretude de algoritmos recursivos
- Prova por indução