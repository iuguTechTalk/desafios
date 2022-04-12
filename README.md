# Desafios de Páscoa
Escolha o seu desafio e submeta na pasta correspondente ao nível e boa sorte!
# Nível I
## Premiação: Gato mia Cacau Show
Você poderá fazer quantos exercícios quiser, a premiação se dará por ordem de entrega de resposta correta, limitada ao número de 1 entrega por desafio enquanto durarem os estoques de prêmios.

Exercícios:
1) Escreva um shell script que ao ser chamado printe na tela do número 1 ao 99, um número por linha.

2)Escreva em shell script ou ruby o desafio abaixo.
Dados dois inteiros, encontre sua soma, diferença, produto e quociente.
Formato de entrada (stdin)
Duas linhas contendo um inteiro cada.
Formato de saída (stdout)
Quatro linhas contendo a soma (), diferença (), produto () e quociente (), respectivamente.Ao calcular o quociente, imprima apenas a parte inteira.
Entrada
5
2
Saída
7
3
10
2

3)Resolva em qualquer linguagem
João e Maria criaram um problema cada. Um revisor classifica os dois desafios, atribuindo pontos em uma escala de 1 a 100 para três categorias: clareza do problema, originalidade e dificuldade.
A classificação para o desafio de Maria é a trinca a = (a[0], a[1], a[2]), e a classificação para o desafio de João é a trinca b = (b[0], b[1], b [2]).
A tarefa é encontrar seus pontos de comparação comparando a[0] com b[0], a[1] com b[1] e a[2] com b[2].
Se a[i] > b[i], então Maria recebe 1 ponto.
Se a[i] < b[i], João recebe 1 ponto.
Se a[i] = b[i], então nenhuma das pessoas recebe um ponto.
Os pontos de comparação são o total de pontos que uma pessoa ganhou.
Dados a e b, determine seus respectivos pontos de comparação.
Exemplo
a = [1, 2, 3] (maria)
b = [3, 2, 1] (joão)
Para os elementos *0*, João recebe um ponto.
Para os elementos iguais a[1] e b[1], nenhum ponto é ganho.
Finalmente, para os elementos 2, a[2] > b[2] então Maria recebe um ponto.
A matriz de retorno é [1, 1] com a pontuação de Maria primeiro e a de João em segundo.
Descrição da função
A função tem os seguintes parâmetros:
um inteiro com classificação de desafio de Maria
um inteiro com classificação de desafio de João
Retornar
A pontuação de cada um, sendo que Maria está na primeira posição e a pontuação de João está na segunda.

Formato de entrada
A primeira linha contém 3 inteiros separados por espaço, a[0], a[1] e a[2], os respectivos valores no tripleto a.
A segunda linha contém 3 inteiros separados por espaço, b[0], b[1] e b[2], os respectivos valores no tripleto b.
Entrada
5 6 7
3 6 10
Saída 
1 1


4)Resolva em qualquer linguagem. Neste desafio, você deve calcular e imprimir a soma dos elementos em uma matriz, tendo em mente que alguns desses inteiros podem ser bem grandes.
Descrição da função
escreva uma função que deve retornar a soma de todos os elementos do array. A função tem os seguintes parâmetros:
ar[n], uma matriz de inteiros.
Retornar
A soma de todos os elementos do array
Formato de entrada
A primeira linha da entrada consiste em um inteiro.
A próxima linha contém inteiros separados por espaço contidos na matriz.
Formato de saída
Retorna a soma inteira dos elementos na matriz.
Exemplo
Entrada
5
1000000001 1000000002 1000000003 1000000004 1000000005
Saída
5000000015

5)Resolva em qualquer linguagem. Dada uma matriz de avistamentos de pássaros em que cada elemento representa um id de tipo de pássaro, determine o id do tipo avistado com mais frequência. Se mais de 1 tipo tiver sido detectado nesse valor máximo, retorne o menor de seus ids.
Exemplo
array = [1,1,2,2,3]
Existem dois tipos de cada um pra 1 e 2 e um avistamento do tipo 3 . Escolha o menor dos dois tipos vistos duas vezes: tipo 1.
Descrição da função
Escreva uma função que tem os seguintes parâmetros: os tipos de aves avistadas
Devoluções
o ID de tipo mais baixo das aves avistadas com mais frequência
Formato de entrada
A primeira linha contém um inteiro, n, o tamanho de array.
A segunda linha descreve array os inteiros n separados por espaço, cada um um número de tipo do pássaro avistado.

É garantido que cada tipo é 1,2, 3, 4, ou 5 .
Entrada
6
1 4 4 4 5 3
Saída
4

6)Resolva em qualquer linguagem. 
Dado um horário no formato AM/PM de -hora, converta-o para o horário militar (24 horas).

Nota: - 00:00:00 em um relógio de 12 horas é 00:00:00 em um relógio de 24 horas.
- 12:00:00 PM em um relógio de 12 horas é 12:00:00 em um relógio de 24 horas.

Exemplo


Retorne '12:01:00'.


Retorna '00:01:00'.

Descrição da função

Complete a função timeConversion no editor abaixo. Ele deve retornar uma nova string representando a hora de entrada no formato de 24 horas.

timeConversion tem os seguintes parâmetros:

string s: uma hora no formato de hora
Devoluções

string: a hora em formato de hora
Formato de entrada

Uma única string que representa uma hora no formato de relógio de hora (ou seja: ou ).

Restrições

Todos os tempos de entrada são válidos
Entrada de Amostra 0

19:05:45
Saída de Amostra 0
19:05:45

7) Corrija os artefatos dockerfile e o dockercompose.yml contidos no repositório da techtalk.

8) Adicione aos artefatos contidos no exercício anterior, um step a mais, que rode pelo menos um arquivo de teste de sua preferência. Obs: o teste pode ter qualquer implementação, como por exemplo, um teste de uma rota nova criada existe. 




# Nivel II
## Premiação: Cesta Cacau Show
Serão apenas três premiações, cada premiação se dará por ordem de entrega de resposta correta.
Você poderá escolher um ou dois dos exercícios a seguir para completar este desafio.
Resolva em qualquer linguagem (ruby, python, php, java, Go, C...). 

Exercícios:
1)Definimos um quadrado mágico como uma matriz n x n de inteiros positivos distintos de 1 a n2 (ao quadrado) onde a soma de qualquer linha, coluna ou diagonal de comprimento é sempre igual ao mesmo número: a constante "mágica".
Você receberá uma matriz *s* de 3x3 inteiros no intervalo de [1,9]. Podemos converter qualquer dígito A em qualquer dígito B no intervalo [1,9] ao custo de a - b. Dado *s*, converta em um quadrado mágico a um custo mínimo. Imprima este custo em uma nova linha.
Nota: O quadrado mágico resultante deve conter números inteiros distintos no intervalo [1,9] .
Exemplo
$s = [[5, 3, 4], [1, 5, 8], [6, 4, 2]]
A matriz fica assim:
5 3 4
1 5 8
6 4 2
Podemos convertê-lo para o seguinte quadrado mágico:
8 3 4
1 5 9
6 7 2
Isso levou três substituições a um custo de 
(5 - 8) (s[0][0])
+ 
(8 - 9) (s[1][2])
+ 
(4 - 7) (s[2][1])

= 7.
Descrição da função
A função tem o(s) seguinte(s) parâmetro(s): um array de inteiros
Devoluções
o custo total mínimo de converter o quadrado de entrada em um quadrado mágico
Formato de entrada
Cada uma das linhas contém três inteiros separados por espaço, representando s[i] .
Restrições
Entrada 
4 9 2
3 5 7
8 1 5
Saída
1


2)
3)
4)



# Nível III
## Premiação: Cesta Top Cacau Show
Um master prêmio para a primeira entrega de resposta correta.
Você pode escolher um dos dois exercícios a seguir para completar este desafio.

Exercícios:

1)
2)
