Algoritmo "Hexagono"

var
   n1, n2, volume:real
   
inicio
   //Entrada de dados
   escreva("Digite a altura da piramide em metros: ")
   leia(n1)
   
   escreva("Digite a aresta do hexágono em metros: ")
   leia(n2)
   
   //Operações
   volume <- ((3 * (n2 ^ 2) * (3 ^ (1/2) ) ) / 6) * n1
   
   //Saída de dados
   escreva("O VOLUME DA PIRAMIDE E = ", volume, " METROS CÚBICOS")
fimalgoritmo
