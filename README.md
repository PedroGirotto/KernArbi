# KernArbi
Função para calcular Equação Integral de FredHolm de 2° espécie
A função KernArbi é baseada no método de Kérneis Arbitrários para as Equações Integrais de Fredholm.

A função KernArbi solicitará 6 parâmetros de entrada:
Primeiro Parâmetro K(x,t):
	Função Kernel na qual depende das variáveis x e t

Segundo Parâmetro F(x):
	Função F na qual depende da variável x

Terceiro Parâmetro:
	O limite superior da integral

Quarto Parâmetro:
	O limite inferior da integral

Quinto Parâmetro:
	O tamanho máximo das matrizes que será utilizado para calcular as determinantes

Sexto Parâmetro:
	Se o usuário quer que as operções internas sejam imprimidas, isso inclui imprimir as matrizes, os determinantes das submatrizes principais.

A função KernArbi retornará uma equação dependente de x e Lambda
