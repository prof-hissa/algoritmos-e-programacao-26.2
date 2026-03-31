# 📘 Lista de Exercícios – Condicionais (Avançado)

---

## Exercício 1 – Sistema de aprovação completo

Peça ao usuário:

* nome do aluno
* nota 1
* nota 2
* número de faltas

Calcule a média e aplique as regras:

* Média ≥ 7 **e** faltas ≤ 25 → Aprovado
* Média ≥ 5 **e** faltas ≤ 25 → Recuperação
* Média < 5 → Reprovado por nota
* Faltas > 25 → Reprovado por falta

Exiba uma mensagem completa com nome, média e situação.

💡 Desafio: combinar condições com `and`

---

## Exercício 2 – Cálculo de salário com múltiplos adicionais

Peça:

* salário base
* anos de empresa
* número de dependentes

Regras:

* Bônus por tempo:

  * ≥ 10 anos → +20%
  * 5 a 9 anos → +10%
  * < 5 anos → +5%

* Bônus por dependentes:

  * cada dependente adiciona R$100

Calcule o salário final e exiba todos os componentes do cálculo.

💡 Desafio: aplicar mais de uma regra ao mesmo valor

---

## Exercício 3 – Sistema de notas com conceito e situação

Peça:

* três notas

Calcule a média e classifique:

**Conceito:**

* ≥ 9 → A
* ≥ 7 → B
* ≥ 5 → C
* < 5 → D

**Situação:**

* A ou B → Aprovado
* C → Recuperação
* D → Reprovado

Exiba:

* média
* conceito
* situação

💡 Desafio: reutilizar a mesma variável em múltiplas decisões

---

## Exercício 4 – Simulação de compra com múltiplas condições

Peça:

* valor da compra
* forma de pagamento (`dinheiro`, `pix`, `cartao`)
* número de parcelas (se for cartão)

Regras:

* Dinheiro ou PIX → 10% de desconto
* Cartão:

  * 1x → 5% de desconto
  * 2x até 4x → valor normal
  * > 4x → acréscimo de 10%

Calcule e exiba o valor final.

💡 Desafio: usar `if` dentro de outro `if` (condicional aninhada)

---

## Exercício 5 – Classificação de temperatura com múltiplos critérios

Peça:

* temperatura (em °C)
* umidade (%)

Classifique:

* Temp < 15 → Frio
* 15 a 30 → Agradável
* > 30 → Quente

Agora combine com a umidade:

* Quente + umidade > 70 → "Abafado"
* Quente + umidade ≤ 70 → "Seco"
* Frio + umidade > 70 → "Frio úmido"
* Frio + umidade ≤ 70 → "Frio seco"

Exiba a classificação completa.

💡 Desafio: múltiplas variáveis influenciando o resultado

---
