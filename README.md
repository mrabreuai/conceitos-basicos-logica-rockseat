# Conectivos Lógicos e Tabela Verdade

**Disciplina:** Algoritmos e Lógica de Programação  
**Instituição:** UniFECAF + Rockseat  
**Aluna:** Marcia Regina de Abreu

## Sobre o Projeto

Exercícios práticos de representação lógica utilizando conectivos e tabelas verdade. Cada sentença do cotidiano foi traduzida para uma expressão lógica formal, com análise de todas as combinações possíveis de Verdadeiro (V) e Falso (F).

## As Regras dos Conectivos

| Conectivo | Símbolo | Regra |
|-----------|---------|-------|
| E (conjunção) | ∧ | Verdadeiro apenas se ambas forem verdadeiras |
| OU (disjunção) | ∨ | Verdadeiro se pelo menos uma for verdadeira |
| SE...ENTÃO (condicional) | → | Falso apenas quando p é V e q é F |
| SE E SOMENTE SE (bicondicional) | ↔ | Verdadeiro quando ambas têm o mesmo valor |

## Exercícios

### 1. Eu estudei para a prova **e** fiz todos os exercícios.

**Conectivo:** E (∧)  
**Proposições:**
- p: Eu estudei para a prova
- q: Fiz todos os exercícios

**Expressão:** `p ∧ q`

| p | q | p ∧ q |
|---|---|-------|
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | F |

### 2. Eu vou ao cinema **ou** fico em casa assistindo séries.

**Conectivo:** OU (∨)  
**Proposições:**
- p: Eu vou ao cinema
- q: Fico em casa assistindo séries

**Expressão:** `p ∨ q`

| p | q | p ∨ q |
|---|---|-------|
| V | V | V |
| V | F | V |
| F | V | V |
| F | F | F |

### 3. **Se** eu acordar cedo, **então** conseguirei pegar o ônibus.

**Conectivo:** SE...ENTÃO (→)  
**Proposições:**
- p: Acordar cedo
- q: Conseguirei pegar o ônibus

**Expressão:** `p → q`

| p | q | p → q |
|---|---|-------|
| V | V | V |
| V | F | F |
| F | V | V |
| F | F | V |

### 4. **Se** eu estudar muito, **então** passarei na prova **e** ganharei um presente.

**Conectivos:** SE...ENTÃO (→) e E (∧)  
**Proposições:**
- p: Estudar muito
- q: Passarei na prova
- r: Ganharei um presente

**Expressão:** `p → (q ∧ r)`

| p | q | r | q ∧ r | p → (q ∧ r) |
|---|---|---|-------|-------------|
| V | V | V | V | V |
| V | V | F | F | F |
| V | F | V | F | F |
| V | F | F | F | F |
| F | V | V | V | V |
| F | V | F | F | V |
| F | F | V | F | V |
| F | F | F | F | V |

### 5. Eu vou jogar videogame **ou** vou estudar lógica de programação.

**Conectivo:** OU (∨)  
**Proposições:**
- p: Jogar videogame
- q: Estudar lógica de programação

**Expressão:** `p ∨ q`

| p | q | p ∨ q |
|---|---|-------|
| V | V | V |
| V | F | V |
| F | V | V |
| F | F | F |

### 6. Eu comi pizza **e** tomei refrigerante.

**Conectivo:** E (∧)  
**Proposições:**
- p: Comi pizza
- q: Tomei refrigerante

**Expressão:** `p ∧ q`

| p | q | p ∧ q |
|---|---|-------|
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | F |

### 7. **Se** eu tiver dinheiro, **então** viajarei nas férias.

**Conectivo:** SE...ENTÃO (→)  
**Proposições:**
- p: Eu tiver dinheiro
- q: Viajarei nas férias

**Expressão:** `p → q`

| p | q | p → q |
|---|---|-------|
| V | V | V |
| V | F | F |
| F | V | V |
| F | F | V |

### 8. Eu lerei um livro **se** e **somente se** terminar meu trabalho.

**Conectivo:** SE E SOMENTE SE (↔)  
**Proposições:**
- p: Eu lerei o livro
- q: Terminar meu trabalho

**Expressão:** `p ↔ q`

| p | q | p ↔ q |
|---|---|-------|
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | V |

### 9. **Se** estiver sol, **então** irei à praia ou ao parque.

**Conectivos:** SE...ENTÃO (→) e OU (∨)  
**Proposições:**
- p: Estiver sol
- q: Irei à praia
- r: Irei ao parque

**Expressão:** `p → (q ∨ r)`

| p | q | r | q ∨ r | p → (q ∨ r) |
|---|---|---|-------|-------------|
| V | V | V | V | V |
| V | V | F | V | V |
| V | F | V | V | V |
| V | F | F | F | F |
| F | V | V | V | V |
| F | V | F | V | V |
| F | F | V | V | V |
| F | F | F | F | V |

### 10. Eu farei um bolo **se** e **somente se** comprar os ingredientes.

**Conectivo:** SE E SOMENTE SE (↔)  
**Proposições:**
- p: Eu farei o bolo
- q: Comprar os ingredientes

**Expressão:** `p ↔ q`

| p | q | p ↔ q |
|---|---|-------|
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | V |

## Conclusão

Os exercícios demonstram como situações do cotidiano podem ser representadas por expressões lógicas formais. A tabela verdade é a ferramenta que permite analisar sistematicamente todos os cenários possíveis sendo a base fundamental tanto para a lógica matemática quanto para a programação de computadores.
