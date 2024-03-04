# Projeto SO 22/23 Simulação de uma Discoteca!
## Alunos: 
- Filipe Lopes - 2048619
- Tom Mendonça - 2049919
- José Branco  - 2034117

## Instruções para colocar o projeto a funcionar:

1. Executar o comando make clean e depois o comando make.
2. Ligar o monitor.
3. Ligar o simulador.
4. Executar o Projeto.

Nota: O simulador só executa depois do monitor se ter ligado.

**Usamos os sockets sockets-unix-stream, dados pelos professores, no nosso projeto**

Possível problema, utilizador de MAC!
Poderá ser necessário a instalação do gcc compiler.

*Para conseguir efetuar compilações com gcc no Ubuntu poderá ser necessário efetuar a instalação:
https://linuxize.com/post/how-to-install-gcc-compiler-on-ubuntu-18-04/

## Acontecimentos do Projeto

60 : Abertura da Discoteca <br />
69 : Encerramento da Discoteca <br />
<br />
00 : Entrada - Discoteca <br />
01 : Entrada - Pista de Dança <br />
02 : Entrada - Zona VIP <br />
03 : Entrada - WC <br />
04 : Entrada - Restaurante <br />
05 : Entrada - Restaurante-Buffet <br />
<br />
10 : Espera na fila - Discoteca <br />
11 : Espera na fila - Pista de Dança <br />
12 : Espera na fila - Zona VIP <br />
13 : Espera na fila - WC <br />
<br />
20 : Desistência da fila - Discoteca <br />
21 : Desistência da fila - Pista de Dança <br />
22 : Desistência da fila - Zona VIP <br />
23 : Desistência da fila - WC <br />
<br />
30 : Saída - Discoteca <br />
31 : Saída - Pista de Dança <br />
32 : Saída - Zona VIP <br />
33 : Saída - WC <br />
34 : Saída - Restaurante <br />
35 : Saída - Restaurante-Buffet <br />
38 : Saída - Expulso da Zona VIP <br />
39 : Saída - Expulso da Discoteca <br />
<br /> 
41 : Fila cheia - Pista de Dança <br />
42 : Fila cheia - Zona VIP <br />
43 : Fila cheia - WC <br />
44 : Fila cheia - Restaurante <br />
