# 📘 Lista – Condicionais + match-case (Avançado)

---

## Exercício 1 – Classificação de senha

Peça uma senha ao usuário.

Analise:

* tamanho da senha
* presença de números

Classifique:

* forte
* média
* fraca

💡 Pesquisar:

* `len()`
* `isdigit()`
* `"0" in senha`

---

## Exercício 2 – Formatação de nome avançada

Peça o **nome completo** do usuário.

Mostre:

* nome completo
* primeiro nome
* último nome
* iniciais (ex: J.S.S)

💡 Pesquisar:

* `split()`
* indexação de listas

---

## Exercício 3 – Sistema de login com níveis de acesso

Peça:

* usuário
* senha

Use `if` para validar:

* admin / 123 → acesso total
* user / 123 → acesso limitado
* qualquer outro → acesso negado

Depois use `match-case` para exibir:

* "Painel administrativo"
* "Painel do usuário"
* "Erro de login"

💡 Desafio: separar autenticação de exibição

---

## Exercício 4 – Classificação de texto

Peça ao usuário uma frase.

Mostre:

* quantidade de caracteres
* quantidade de palavras
* frase em maiúsculo
* frase sem espaços no início e fim

💡 Pesquisar:

* `len()`
* `split()`
* `strip()`

---

# 🔥 Exercício 5 – Sistema completo de pedido

Crie um pequeno sistema de pedido com as seguintes etapas:

### Entrada de dados:

Peça ao usuário:

* nome
* nome do produto
* categoria do produto (`eletronico`, `alimento`, `vestuario`)
* preço do produto
* quantidade
* forma de pagamento (`pix`, `cartao`)

---

### Regras:

### 1. Subtotal

Calcule:

```text
subtotal = preço * quantidade
```

---

### 2. Desconto por categoria (usar `match-case`)

* eletrônico → 5%
* alimento → 10%
* vestuário → 15%

---

### 3. Desconto por pagamento

* PIX → +5%
* Cartão → sem desconto

---

### 4. Frete

* subtotal ≥ 200 → frete grátis
* caso contrário → frete = 20

---

### 5. Nome formatado

Exiba o nome do cliente:

* em maiúsculo
* com primeira letra maiúscula

---

### 6. Resumo final

Exiba:

* nome do cliente
* produto
* subtotal
* valor do desconto
* valor do frete
* valor final

---

💡 Pesquisar:

* `upper()`
* `title()`
* formatação com `:.2f`

---
