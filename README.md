# Gerenciamento de Conjuntos

Trabalho acadêmico proposto pela disciplina de Linguagem de Programação do curso de Análise e Desenvolvimento de Sistemas (UDESC).
Em parceria com Eduarda Stipp Rech - @dud4rech


## :dart: Objetivo

Implementar um programa que gerencia uma quantidade indeterminada de conjuntos de valores inteiros. O modelo consiste no uso de uma matriz MxN, sendo M e N constantes.
* Cada linha da matriz é usada para representar um conjunto de valores, sendo que o programa deve
garantir que os limites da matriz não sejam ultrapassados. Portanto, não deve ser possível criar mais do
que M conjuntos, e cada conjunto não pode ter mais do que N valores;
* A matriz deve ser inicializada com zeros, indicando que está vazia. O zero, portanto, não é considerado
como um valor válido;
* Além da matriz, o programa deve utilizar um contador para registrar quantidade de conjuntos. Portanto, o
contador também deve estar zerado ao início do programa.


### O programa deve ficar em um ciclo de repetições, oferecendo um menu de texto com as seguintes opções:

1. Criar um novo conjunto vazio;
2. Inserir dados em um conjunto;
3. Remover um conjunto;
4. Fazer a união entre dois conjuntos;
5. Fazer a intersecção entre dois conjuntos;
6. Mostrar um conjunto;
7. Mostrar todos os conjuntos;
8. Busca por um valor;
9. Sair do programa.
