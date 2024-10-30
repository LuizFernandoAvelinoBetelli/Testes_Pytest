## Testes Unitários com Pytest
Este projeto é uma introdução à criação de testes unitários em Python utilizando o framework de testes Pytest. O código inclui uma função simples de soma e testes que verificam seu funcionamento com diferentes cenários.

## Estrutura do Projeto
TestesPytest.py: Contém a função soma_total, que realiza a soma de preços em uma lista, além dos testes unitários que verificam seu comportamento.
Pytest Cache: Armazena cache de execução do Pytest para otimizar o desempenho dos testes.

## Funcionalidades

Função soma_total(precos): Recebe uma lista de preços e retorna a soma de todos os itens.
Testes:
Teste com uma lista de preços padrão para verificar se a soma é correta.
Teste com uma lista vazia para verificar se a função retorna zero.

## Tecnologias Utilizadas

Python: Linguagem de programação principal.
Pytest: Framework para criação e execução dos testes.

## Como Executar

- Instale o Python caso ainda não esteja instalado.
  
- https://www.python.org/downloads/
  
  Instale o Pytest caso ainda não esteja instalado:

- pip install pytest

  Execute os testes com o comando:

- pytest TestesPytest.py

  

# Resultados Esperados

O teste deve passar com sucesso quando a soma da lista de preços for igual ao valor esperado.
O teste com uma lista vazia deve retornar zero, garantindo que a função lida corretamente com listas sem itens.
