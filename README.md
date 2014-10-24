Máquina de Turing Universal
========

#Descrição
A Máquina de Turing Universal (MTU) consiste em uma Máquina de Turing (MT) que recebe como entrada uma outra Máquina de Turing e uma entrada para esta e a executa sob essa entrada. O projeto consiste em implementar uma Máquina de Turing Universal Determinística (além de ser determinística, a entrada será uma Máquina de Turing determinística) conforme a especificação que segue:

# Símbolos
\# - divisor de transições.

q1 - estado inicial.

q1..1 - outros estados (q11 é o segundo, q111 é o terceiro, etc.).

f - estado final.

a1 - letra do alfabeto da MT.

a1..1 - outras letras do alfabeto.

R/L - direita/esquerda.

$ - divisor entre a MT e a palavra a ser testada.

A - onde está o cabeçote da MT.

Caso a MT seja válida e a palavra funcione para a MT, deve ser colocado "#aceito" ao final da palavra recebida na MTU, exemplo:

q1a1a11Rq11#q11a11a111Lf#q11a1a11Rq1$A11a111#aceito

Caso a MT seja válida e a palavra NÃO funcione, deve ser colocado "#rejeitado".

Caso a MT NÃO seja válida, a MTU não parará, isso significa que a entrada não foi válida.
