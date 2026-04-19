# Lista de Exercícios – Nível Avançado (Algoritmos e Matrizes)

---

## Exercício 1 – Cálculo de fatorial

O fatorial de um número é o resultado da multiplicação desse número por todos os seus antecessores até 1.

Exemplo:

* 5! = 5 × 4 × 3 × 2 × 1 = 120

Peça ao usuário um número inteiro N e calcule o seu fatorial.

---

### Exemplo

Entrada:

```
5
```

Saída:

```
120
```

---

## Exercício 2 – Sequência de Fibonacci

A sequência de Fibonacci é uma sequência de números onde cada termo é a soma dos dois anteriores.

Exemplo:

```
0, 1, 1, 2, 3, 5, 8, ...
```

Peça ao usuário um número N e exiba os N primeiros termos da sequência.

---

### Exemplo

Entrada:

```
6
```

Saída:

```
0 1 1 2 3 5
```

---

## Exercício 3 – Verificador de número primo

Um número primo é aquele que é divisível apenas por 1 e por ele mesmo.

Exemplos:

* 7 é primo
* 8 não é primo

Peça ao usuário um número inteiro e verifique se ele é primo. Dica: Use divisões sucessivas

---

### Exemplo

Entrada:

```
7
```

Saída:

```
Primo
```

Entrada:

```
8
```

Saída:

```
Não primo
```

---

## Exercício 4 – Soma dos dígitos de um número

Peça ao usuário um número inteiro.

Calcule a soma de todos os seus dígitos.

---

### Exemplo

Entrada:

```
1234
```

Saída:

```
10
```

---

## Exercício 5 – Desenhos em grade 32x32

Crie um programa que desenhe padrões em uma grade de **32 x 32 posições**.

Cada posição deve exibir:

* `*` para representar o desenho
* espaço `" "` para o restante

Use laços aninhados e condicionais.

---

### Parte A – Diagonal principal

Desenhe uma linha diagonal do canto superior esquerdo até o canto inferior direito.

Exemplo (reduzido):

```
*       
  *      
    *     
      *    
```

---

### Parte B – Diagonal secundária

Desenhe uma linha diagonal do canto superior direito até o canto inferior esquerdo.

Exemplo (reduzido):

```
       *
     * 
   *  
 *   
```

---

### Parte C – X completo

Combine as duas diagonais formando um X.

Exemplo (reduzido):

```
*       *
  *   * 
    *  
  *   * 
*       *
```

---

### Parte D – Quadrado (moldura)

Desenhe apenas a borda de um quadrado.

Exemplo (reduzido):

```
********
*      *
*      *
********
```

---

### Parte E – Círculo (desafio)

Desenhe uma forma aproximada de um círculo dentro da matriz.

Exemplo (reduzido):

```
   *****   
  *******  
 ********* 
 ********* 
  *******  
   *****   
```

---

### Dicas

* Pense em como o computador percorre linhas e colunas
* Use variáveis como `linha` e `coluna`
* Descubra em quais posições o caractere deve ser desenhado
* Para o círculo, pesquise como calcular distância entre pontos
* Teste com matrizes menores antes de usar 32x32
