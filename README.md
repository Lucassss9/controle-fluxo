# Desafio Controle de Fluxo – Java Básico

## Descrição do Projeto
Este projeto tem como objetivo praticar o **controle de fluxo** em Java, utilizando `if`, `for`, tratamento de exceções e criação de **exceções personalizadas**. O programa recebe dois números inteiros via terminal e imprime uma contagem incremental com base na diferença entre eles. Caso o primeiro número seja maior que o segundo, é lançada uma **exceção personalizada** (`ParametrosInvalidosException`) para tratar o erro de entrada.

---

## Funcionalidades
- Recebe dois parâmetros inteiros do usuário pelo terminal.
- Valida se o segundo número é maior que o primeiro:
  - Se sim, realiza a contagem e imprime no console:
    ```
    Imprimindo o número 1
    Imprimindo o número 2
    ...
    ```
  - Se não, lança uma exceção `ParametrosInvalidosException` com a mensagem:
    ```
    O segundo parâmetro deve ser maior que o primeiro.
    ```
- Utiliza **métodos estáticos** e **exceções checadas (checked exceptions)**.

---

## Estrutura do Projeto
DesafioControleFluxo/

│

├─ src/

│ ├─ Contador.java # Classe principal com o método main e lógica de contagem

│ └─ exception/

│ └─ ParametrosInvalidosException.java # Exceção personalizada

## Tecnologias Utilizadas
- **Java (Orientação a Objetos)**
- **Controle de fluxo** (`if`, `for`)
- **Exceções personalizadas** (`Exception`)
- **Scanner** para entrada do usuário

---

## Autor do Desafio
**Gleyson Sampaio** – autor do desafio na DIO, Trilha Java Básico  
Link: [Repositório GiHub](https://github.com/digitalinnovationone/trilha-java-basico/tree/main/desafios/controle-fluxo)

## Realização do Exercício
**[Lucas]** – realizei este exercício como prática.




