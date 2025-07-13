as condições dão caminhos diferentes para resolver um problema.

se - if condição:

bloco True

senão - else:

bloco false

ex:

tempo = int(input("Quantos anos tem seu carro"))
if tempo <=3:
print('carro novo')
else:
print('carro velho')

ou também podemos fazer.

tempo = int(input("Quantos anos tem seu carro"))
print('carro novo' if tempo <=3 else 'carro velho')