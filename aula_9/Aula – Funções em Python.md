# Aula – Funções em Python

## O que são funções?

Funções são blocos de código reutilizáveis criados para executar tarefas específicas.

Elas ajudam a:

* organizar melhor o código
* evitar repetição
* facilitar manutenção
* dividir problemas grandes em partes menores

---

## Estrutura básica de uma função

```python
# definição da função

def saudacao():
    print("Olá!")

# chamada da função
saudacao()
```

---

## Explicação

```python

def saudacao():
```

* `def` → palavra reservada usada para criar funções
* `saudacao` → nome da função
* `()` → parâmetros da função
* `:` → início do bloco da função

---

## Exemplo 1 – Função simples

```python

def mensagem():
    print("Bem-vindo ao Python")

mensagem()
```

Saída:

```text
Bem-vindo ao Python
```

---

# Parâmetros

Funções podem receber valores chamados parâmetros.

---

## Exemplo 2 – Função com parâmetro

```python

def saudacao(nome):
    print("Olá", nome)

saudacao("João")
saudacao("Maria")
```

Saída:

```text
Olá João
Olá Maria
```

---

## Exemplo 3 – Soma de números

```python

def soma(a, b):
    resultado = a + b
    print(resultado)

soma(10, 5)
soma(3, 8)
```

---

# Retorno de valores

Funções podem devolver valores usando `return`.

---

## Exemplo 4 – Retornando resultado

```python

def soma(a, b):
    return a + b

resultado = soma(4, 6)

print(resultado)
```

Saída:

```text
10
```

---

## Diferença entre `print` e `return`

### Usando `print`

```python

def soma(a, b):
    print(a + b)
```

* apenas exibe o resultado
* não devolve valor

---

### Usando `return`

```python

def soma(a, b):
    return a + b
```

* devolve o valor
* permite reutilização em outras operações

---

# Exemplo 5 – Função com condicional

```python

def verificar_par(numero):
    if numero % 2 == 0:
        return "Par"
    else:
        return "Ímpar"

print(verificar_par(8))
print(verificar_par(5))
```

---

# Exemplo 6 – Função com laço

```python

def tabuada(numero):
    i = 1

    while i <= 10:
        print(numero, "x", i, "=", numero * i)
        i += 1

# chamada

tabuada(5)
```

---

# Escopo de variáveis

Variáveis criadas dentro da função existem apenas dentro dela.

---

## Exemplo 7 – Escopo local

```python

def teste():
    mensagem = "Olá"
    print(mensagem)

# funciona

teste()

# erro

print(mensagem)
```

---

# Funções com múltiplos retornos

```python

def operacoes(a, b):
    soma = a + b
    multiplicacao = a * b

    return soma, multiplicacao

resultado1, resultado2 = operacoes(3, 4)

print(resultado1)
print(resultado2)
```

---

# Boas práticas

* usar nomes claros
* criar funções pequenas
* evitar repetir código
* separar responsabilidades

---

# Exercícios

---

## Exercício 1 – Saudação

Crie uma função chamada `saudacao()` que exiba:

```text
Olá, mundo!
```

---

## Exercício 2 – Nome do usuário

Crie uma função que receba um nome como parâmetro e exiba:

```text
Olá João
```

---

## Exercício 3 – Soma

Crie uma função que receba dois números e retorne a soma.

---

## Exercício 4 – Maior número

Crie uma função que receba dois números e retorne o maior.

---

## Exercício 5 – Número par

Crie uma função que receba um número e retorne:

```text
Par
```

ou

```text
Ímpar
```

---

## Exercício 6 – Média

Crie uma função que receba 3 notas e retorne a média.

---

## Exercício 7 – Tabuada

Crie uma função que receba um número e exiba sua tabuada de 1 a 10.

---

## Exercício 8 – Fatorial

Crie uma função que receba um número e calcule o fatorial usando `while`.

---

## Exercício 9 – Contador de vogais

Crie uma função que receba uma palavra e retorne quantas vogais ela possui.

---

## Exercício 10 – Calculadora

Crie funções separadas para:

* soma
* subtração
* multiplicação
* divisão

Depois crie um menu para permitir que o usuário escolha a operação.
