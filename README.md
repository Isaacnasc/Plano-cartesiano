cod1 = float(input('Digite a coordenada X:'))
cod2 = float(input('Digite a coordenada Y:'))

if cod1 > 0 and cod2 > 0:
    print('Primeiro quadrante.')
elif cod1 < 0 and cod2 > 0:
    print('Segundo quadrante.')
elif cod1 < 0 and cod2 < 0:
    print('Terceiro quadrante.')
elif cod1 > 0 and cod2 < 0:
    print('Quarto quadrante.')
else:
    print('O ponto está no eixo ou origem.')
