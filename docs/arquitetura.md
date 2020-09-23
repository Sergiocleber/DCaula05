# Arquittetura

* As funções relacionadas ao gerenciamento das casas do jgo da velha ficarão no módulo **jogovelha.py**

* O estado de cada casa do jogo será representada por uma string: "." para casa vazia; "X" oara casa ocupada pelo 1º jogador; "O" para casa ocupada pelo 2º jogador.

* mA função inicializar() retornará uma lista 3x3, onde cada posição conterá uma string para indicar o estado de uma casa do jogo. A função retornará todas as casa inicialmente vazias.
