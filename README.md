Algoritmo "calculadora."
// 
//  
// Descrição   : calcular as 4 operaçoes basicas
// Autor(a)    : Kaio Bezerra e Yasmin Santos
// Data atual  : 07/05/2022


Var
// Seção de Declarações das variáveis 
x: real
y: real
r: real
opcao: caractere


Inicio
// Seção de Comandos, procedimento, funções, operadores, etc... 
escreval("escolha uma opçao: * Multiplicar;  - Subtrair; + Soma; / Divisao: ")
leia (opcao)
limpatela

  escreva("digite um numero: ")
leia(x)
limpatela



  escreva("digite outro numero: ")
leia(y)

 limpatela
escolha opcao
caso = "*"
      r <- x * Y
caso = "-"
      r <- x - Y
caso = "+"
      r <- x + Y
caso = "/"
      r <- x/Y

 fimescolha



 escreva (x)
 escreva (opcao)
 escreva (y)
escreva("=")
escreva(r)



Fimalgoritmo