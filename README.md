# T2_SISOP

<hr>

## Objetivo

Implementar um simulador de um sistema de gerência de memória paginada de um sistema operacional

O simulador deve receber com entrada uma sequência de endereços virtuais e apresentar como saída os endereços físicos

**OBS:** Qualquer linguagem de programação poderá ser utilizada para o desenvolvimento do trabalho

## Detalhes sobre a implementação

Deve-se informar os seguintes parâmetros para inicialização:

- tamanho da memória virtual
- tamanho da memória física
- tamanho da página

Deve-se criar uma tabela de páginas, podendo ser de 1 ou mais níveis ou até mesmo invertida e, um vetor representando a memória física

o vetor que representa as molduras de memória física deve ser inicializado com zeros e deve ser preenchido sob demanda

a tabela de páginas deve ser inicializada com valores de -1, ou seja, as entradas estão todas livres e deve ser preenchida sob demanda

caso a memória física esteja lotada, o programa deverá parar

## Detalhes sobre a entrada dos dados

A entrada de dados para o simulador consiste em uma sequência de endereços virtuais, que podem ser gerados aleatoriamente
