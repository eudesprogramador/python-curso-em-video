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

# 07-Faça um programa que leia um número interiro qualquer e mostre na tela a sua tabuada.

```
n = int(input('digite um número: '))
print('-' * 12)
print('{} x {} = {:2}'.format(n , 1, n*1))
print('{} x {} = {:2}'.format(n , 2, n*2))
print('{} x {} = {:2}'.format(n , 3, n*3))
print('{} x {} = {:2}'.format(n , 4, n*4))
print('{} x {} = {:2}'.format(n , 5, n*5))
print('{} x {} = {:2}'.format(n , 6, n*6))
print('{} x {} = {:2}'.format(n , 7, n*7))
print('{} x {} = {:2}'.format(n , 8, n*8))
print('{} x {} = {:2}'.format(n , 9, n*9))
print('{} x {} = {:2}'.format(n , 10, n*10))
print('-' * 12)
```

# 08-Crie um programa que leia quanto dinheiro uma pessoa tem na carteira e mostre quantos dólares ela pode comprar.
### OBS: US$1,00 = R$3,27 
```
RS = int(input('digite um valor: '))
US = RS * 3.27
print(RS,'R$ é igual a {} US$ '.format(US))
```


# 09-Faça um programa que leia a largura e a altura de uma parede em metros, calcule a sua área e a quantidade de tinta necessária para pintá-la, sabendo que cada litro de tinta, pinta uma área de 2m².

```
larg = float(input('largura da parede: '))
alt = float(input('altura da parede: '))
área = larg * alt
print('sua parede tem a dimensão de {} x {} e sua área é de {}m².'.format(larg ,alt ,área ))
tinta = área / 2
print('para pintar essa parede, voçê precissará de {}l de tinta.'.format(tinta))
```


