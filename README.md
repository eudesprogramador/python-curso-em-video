# python-curso-em-video
resolução das questões do curso de python do curso em video 
´´´
# 01-Crie um programa que leia dois números e mostre a soma entre eles.

```
n1 = int(input('digite um número '))
n2 = int(input('digite mais um número '))
s = n1 + n2
print('a soma vale',s)
```

# 02-Faça um programa que leia algo pelo teclado e mostre na tela o seu tipo primitivo e todas as informações possiveis sobre ela.

```
a = input('digite algo ')
print('O seu tipo primitivo é ',type(a))
print('So tem espaços? ',a.isspace())
print('É um número? ',a.isnumeric())
print('É alfabetica? ',a.isalpha())
print('É alfanumerico? ',a.isalnum())
print('Esta em maiúsculas? ',a.isuper())
print('Esta em minúsculas? ',a.islower())
print('Esta capitalizada? ',a.istitle())
print('É decimal? ',a.isdecimal())
```

# 03-Faça um programa que leia um número inteiro e mostre seu sucessor e seu antecessor.

```
n = int(input('digite um número '))
a = n - 1
b = n + 1
print('O número escolhido foi {},seu antecessor é {},e seu sucessor é {}'.format( n , a , b ))
```

# 04-Crie um algoritimo que leia um número e mostre o seu dobro,triplo e raiz quadrada.

```
n = int(input('digite um número: '))
d = n * 2
t = n * 3
r = n ** (1/2)
print('O dobro de {} vale {}. '.format( n , d ))
print('O triplo de {} vale {}. '.format( n , t ))
print('A raiz quadrada de {} é igual à {:.2f}. '.fotmat( n , r ))
```

# 05-Desolvalva um programa que leia as duas notas de aluno, calcule e mostre a sua média.

```
n1 = int(input('nota 01: '))
n2 = int(input('nota 02: '))
M = ( n1 + n2 ) / 2
print('sua média é ',M)
```

# 06-Escreva um programa que que leia o valor em metros e o exiba convertido em centímetros e em milímetros.

```
print('CONVERSOR DE MEDIDAS')
m = int(input('Digite um valor em metros: '))
c = m * 100
mm = m * 1000
print('metros: {}m'.format( m ))
print('centímetros: {}cm \nmilímetros: {}mm '.format( c , mm ))
```

# 07- 
