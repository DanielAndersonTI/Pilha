# Pilha com Exceções Personalizadas e Testes Unitários

Este projeto implementa uma **estrutural de dados Pilha** com operações básicas como empilhar, desempilhar, verificar o topo e o tamanho, e **trata exceções personalizadas** que ocorrem quando operações inválidas são realizadas em uma pilha cheia ou vazia. A implementação também inclui **testes unitários** utilizando o framework **JUnit 5** para garantir o correto funcionamento da pilha e o tratamento das exceções.

## Funcionalidades

- **Pilha**:
  - Método `empilha()`: Empilha um novo elemento na pilha.
  - Método `desempilha()`: Remove e retorna o topo da pilha.
  - Método `topo()`: Retorna o topo da pilha sem removê-lo.
  - Método `estaVazia()`: Verifica se a pilha está vazia.
  - Método `tamanho()`: Retorna o número de elementos na pilha.

- **Exceções Personalizadas**:
  - **PilhaVaziaException**: Lançada quando tenta-se desempilhar de uma pilha vazia.
  - **PilhaCheiaException**: Lançada quando tenta-se empilhar em uma pilha cheia.

- **Testes Unitários**: 
  - Testes automatizados para verificar se a pilha funciona corretamente, incluindo testes para verificar a pilha vazia, empilhamento e desempilhamento de elementos, além da validação das exceções personalizadas.

## Estrutura do Projeto

O projeto é organizado da seguinte forma:

- **`Pilha.java`**: Implementação da pilha e suas operações.
- **`PilhaCheiaException.java`**: Exceção personalizada para pilha cheia.
- **`PilhaVaziaException.java`**: Exceção personalizada para pilha vazia.
- **`testePilha.java`**: Testes unitários utilizando JUnit 5.
