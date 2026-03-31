# Lista de Exercícios – Laços de Repetição (for)

---

### Exercício 1 – Contagem simples

Peça um número ao usuário e exiba todos os números de **1 até esse valor**.

---

### Exercício 2 – Soma acumulada

Peça ao usuário 5 números.

Calcule e exiba a soma total.

---

### Exercício 3 – Média de valores

Peça ao usuário 4 números.

Calcule e exiba a média.

---

### Exercício 4 – Tabuada

Peça um número e exiba sua tabuada de 1 a 10.

---

### Exercício 5 – Contagem regressiva

Peça um número e exiba uma contagem regressiva até 0.

---

### Exercício 6 – Contagem de pares

Peça um número.

Mostre quantos números pares existem entre 1 e esse número.

---

### Exercício 7 – Soma de pares

Peça um número.

Some apenas os números pares até esse valor.

---

### Exercício 8 – Validação simples

Peça um número ao usuário.

Enquanto o número for negativo, peça novamente.

---

### Exercício 9 – Contador de letras

Peça uma palavra.

Conte quantas letras ela possui (sem usar `len()`).

---

### Exercício 10 – Menu repetitivo

Crie um menu:

```text
1 - Olá
2 - Mostrar nome
0 - Sair
```

Repita o menu até o usuário escolher sair.

---

### Exercício 11 – Sistema de notas com repetição

Permita que o usuário digite várias notas (até digitar -1).

Calcule:

* média
* maior nota
* menor nota

---

### Exercício 12 – Simulador de caixa

Crie um sistema que permita adicionar produtos até o usuário digitar "fim".

Para cada produto:

* nome
* preço

Calcule o total da compra.

---

### Exercício 13 – Analisador de texto

Peça uma frase.

Conte:

* número de vogais
* número de consoantes
* número de espaços

💡 Pesquisar:

* `lower()`
* `in`

---

### Exercício 14 – Sistema de login com tentativas

Permita até 3 tentativas de login.

Se acertar, exiba sucesso.

Se errar 3 vezes, bloqueie o acesso.

---

### Exercício 15 – Calculadora com menu contínuo

Crie uma calculadora que:

* mostre um menu de operações
* execute a operação escolhida
* continue rodando até o usuário sair

Use `match-case`.

---

## Desafios Avançados

---

### Exercício 16 – Verificador de números primos

Peça um número.

Verifique se ele é primo.

💡 Desafio: usar laço para testar divisões

---

### Exercício 17 – Sequência de Fibonacci

Peça um número N.

Exiba os N primeiros termos da sequência de Fibonacci.

---

### Exercício 18 – Cifra de César 🔐

Crie um programa que:

* peça uma mensagem
* peça um número de deslocamento

Implemente a **cifra de César**, deslocando cada letra.

Exemplo:

```text
Mensagem: abc
Deslocamento: 2
Saída: cde
```

💡 Pesquisar:

* `ord()` e `chr()`
* manipulação de caracteres

---

### Exercício 19 – Sistema de votação

Permita que vários votos sejam registrados:

* candidato A
* candidato B
* candidato C
* branco

O sistema termina quando o usuário digitar "fim".

Exiba o total de votos de cada.

---

### Exercício 20 – Sistema completo de pedidos

Permita cadastrar vários produtos:

* nome
* preço
* quantidade

Para cada item:

* calcule subtotal
* acumule total geral

Ao final, exiba:

* total da compra
* quantidade total de itens

💡 Desafio: integrar tudo aprendido até agora