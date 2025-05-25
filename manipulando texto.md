frase = 'Curso em vídeo python'
C  u  r  s  o     e  m     V  í  d  e  o      p  y  t  h  o  n
0  1  2  3  4  5  6  7  8  9  10 11 12 13 14 15 16 17 18 19 20

* os espaços também contam
*letras maiusculas é diferente de letra minuscula

=======================================================
>Fatiamento

frase[9] - é igual a V

frase[9:13] - vai pegar do V ate o E, ele para de contar no 13

frase[9:21:2] - vai do 9 até o 21 pulando de 2 em 2

frase[:5] - é a mesma coisa de 0:5, já que eu não indiquei da onde ele vai começar

frase[15:] - vai ir do 15 até o final

frase[9::3] - vai do 9 até o final pulando de 3 em 3

>-----------------------------------------------------------------<

>Análise

len(frase) - vai mostrar quantos carteres tem uma frase

frase.count('o') - contar quantas letra o minusculas tem na frase = 3

frase.count('o',0,13) - vai do 0 até o 12 contando quantos o tem = 1

frase.find('deo') - quando ele encontrou 'deo' na frase = 11

frase.find('Android') -  como essa frase não existe ele vai devolver o valor -1

'curso' in frase - vai mostrar se existe a palavra curso na frase

>-----------------------------------------------------------------<

>Transformação

frase.replace('Python','Android') - subtituiria a palavra python por android

frase.upper() - vai transformar as letras minusculas em maiusculas

frase.lower() - vai transformar as letras maiusculas em minusculas

frase.capitalize() - vai jogar todos os caracteres para minusculos e somente a primeira letra será maiuscula

frase.title() - vai analisar quantas palavras tem na frase e deixar a primeira letra de cada palavra em maiusculo

frase.strip() -  vai remover todos os espaços inuteis do começo e do fim da frase

frase.rstrip() - remove os espaços da direita
frase.lstrip() - remove os espaços da esquerda

>----------------------------------------------------------------<

>Divisão

frase.split() - vai criar uma divisão entre os espaços criando uma nova lista
ex:  

C u r s o   e m   v  i  d  e  o
1 2 3 4 5 6 7 8 9 1 11 12 13 14

ficaria:

C u r s o | e m | v i d e o
1 2 3 4 5 | 1 2 | 1 2 3 4 5

    0        1        2

>--------------------------------------------------------<

>Junção

'-'.join(frase) - vai criar um espaço e colocar um '-' dentro do espaço
 ex:

 Curso-em-video
