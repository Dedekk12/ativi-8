programa {
  leia(lado3)

  se ((lado1 + lado2 > lado3) e (lado2 + lado3 > lado1) e (lado3 + lado1 > lado2)){
  escreva("Seus valores formam um triangulo, parabéns, voce sabe geometria básica! \n")
  escreva("Seus valores formam um triangulo, parabéns, voce sabe geometria básica! \n")

  se ((lado1 == lado2 e lado3 != lado2 e lado3 != lado1) ou (lado2 == lado3 e lado2 != lado1 e lado3 != lado1) ou (lado1 == lado3 e lado3 != lado2 e lado1 != lado2))
  triangulo = "isósceles"
  triangulo = "isósceles"

  se((lado1 == lado2 e lado2 == lado3 e lado3 == lado1))
  triangulo = "equilátero"
  triangulo = "equilátero"

  se((lado1 != lado2 e lado2 != lado3 e lado3 != lado1))
  triangulo = "escaleno"

  escreva("Seu triangulo é ", triangulo)
  escreva("Seu triangulo é ", triangulo)
  } senao { 
    escreva("Seus valores não formam um triangulo:(")
    escreva("Seus valores não formam um triangulo:(")
  }
