Algoritmo "contagem inteligente"
Var
  in,fim,cont:inteiro
Inicio
      escreval ("CONTAGEM INTELIGENTE")
      ESCREVAL ("--------------------")
      ESCREVA("Início: ")
      leia(in)
      escreva("Fim: ")
      leia(fim)
      ESCREVAL ("--------------------")
      ESCREVAL ("  C O N T A N D O")
      ESCREVAL ("--------------------")
      Se (in<=fim) entao
      cont<-in
      enquanto (cont<=fim) faca
               escreva(cont,"..")
               cont<- cont +1
      fimenquanto
      senao
        se (in>fim) entao
        cont<-in
        enquanto (cont>=fim) faca
           escreva(cont,"..")
           cont<- cont - 1
        fimenquanto
        fimse
      fimse
Fimalgoritmo