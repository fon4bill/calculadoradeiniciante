# calculadoradeiniciante
Minha primeira calculadora que fiz vendo algumas aulas, sei que tenho muito, muito a desenvolver... utilizei o visualg por isso 


Var
n1,n2,n3:real
op1:inteiro

Inicio
 escreva("bora fazer uma conta bro? ")
 escreval()
 escreval("digite um numero que deseja fazer a equação: ")
 leia(n1)
 escreval()
 escreval("digite outro numero: ")
 leia(n2)
 escreval()
 escreval("digite o numero respectivo a equação que deseja fazer a operação: ")
 escreval()
 escreval("adição, opção 1:")
 escreval()
 escreval("subtração, opção: 2")
 escreval()
 escreval("multiplicação, opção: 3")
 escreval()
 escreval("divisão, opção: 4")
 leia(op1)
  escreval()
  se (op1 = 1) entao
   n3<- n1 + n2
    escreval("o resultado da adição é "n3)
  senao
     se(op1=2)entao
        n3<-n1 - n2
         escreval("o resultado da subtração é ", n3)
     senao

       se(op1=3)entao
         n3<-n1 * n2
          escreval("o resultado da multiplicação é ",n3)
       senao
          se(op1=4)entao
            se(n2=0)entao
              escreval("a operação não pode ser realizada")
            senao
             se n3<-n1 / n2 entao
             escreval("o resultado da divisão é ",n3)
  fimse   senao
     fimse
       fimse
          fimse
             fimse
Fimalgoritmo
