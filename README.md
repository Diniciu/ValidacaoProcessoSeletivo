# Desafio Controle de Fluxo

Este projeto foi desenvolvido como parte do módulo de **Controle de Fluxo** da plataforma **DIO**. O objetivo é exercitar conceitos de controle de fluxo em Java, utilizando estruturas como `for` e tratamento de exceções.

## Descrição do Desafio

O sistema recebe dois números inteiros como parâmetros via terminal. Com base nesses números, o programa realiza as seguintes operações:

1. **Validação dos Parâmetros**:
   - Se o primeiro número for maior que o segundo, o programa lança uma exceção customizada chamada `ParametrosInvalidosException` com a mensagem:  
     **"O segundo parâmetro deve ser maior que o primeiro"**.

2. **Contagem e Impressão**:
   - Caso os parâmetros sejam válidos, o programa calcula a diferença entre os dois números e realiza uma contagem (usando um loop `for`), imprimindo no console os números incrementados.

## Estrutura do Projeto

O projeto contém as seguintes classes:

- **`Contador`**: Classe principal que contém a lógica de entrada de dados, validação e contagem.
- **`ParametrosInvalidosException`**: Classe que representa a exceção customizada para validação dos parâmetros.

## Tecnologias Utilizadas
 - Java: Linguagem de programação principal.
 - Scanner: Para entrada de dados via terminal.
 - Tratamento de Exceções: Para validação de regras de negócio.
