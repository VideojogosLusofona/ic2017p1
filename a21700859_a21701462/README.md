# 1� Projeto de Introdu��o � Computa��o 2017/2018<p> #

#### Madalena Marcelino (a21700854)
#### Rui Martins (a21701462)

## Descri��o da solu��o ##
Para a realiza��o deste trabalho cri�mos tr�s vari�veis iniciais, uma para receber
o n�mero de perguntas a apresentar ao utilizador, outra para receber a resposta �s
convers�es e uma para registar o n�mero de respostas certas.<p>Ger�mos uma semente
aleat�ria com `srand((unsigned int) time(NULL))`. De seguida, cri�mos um uma
instru��o for com a vari�vel `i` a servir de contador, em que o seu valor inical �
1 e onde ciclo � executado enquanto essa mesma var for menor ou igual que
`nperguntas`.<p>Dentro do ciclo `for` cri�mos duas vari�veis. A uma atribu�mos um
n�mero aleat�rio positivo de 1 a 255 com `(rand()%255)+1` que � utilizado como o
n�mero mostrado ao utilizador para este converter. A outra vari�vel recebe um
n�mero de 1 a 6 atrav�s do mesmo procedimento mas esta serve para ser usada no
`switch` para que possamos ter um 6 casos aleat�rios. <p>Em cada um dos casos
� mostrado o n�mero aleat�rio guardado em `perguntas` como decimal, hexadecimal
ou octal e � pedido ao utilizador que converta o mesmo para uma das outras duas
bases. <p>Ex: No `case 1:` � mostrado o n�mero em octal e o programa pede ao
utilizador para converter para base 10 enquanto que no `case 2` o programa mostra
o n�mero na mesma base mas pede a convers�o para base 16.
<p>Ap�s a resposta por parte do user, caso a convers�o esteja correcta a vari�vel
`rcertas` � incrementada em 1 e � mostrada a mensagem "Certo!" no ecr�. Se a
convers�o estiver errada aparece simplesmente a mensagem "Errado!".
<p>No final de todos os ciclos `for` aparece uma mensagem com o n�mero de vezes
que o user acertou atrav�s da vari�vel `rcertas`.

## Fluxograma
![Fluxograma](fluxograma1.svg)

## Material utilizado para a realiza��o do trabalho ##
- Notepad++
- https://www.draw.io/


## Conclus�es da Mat�ria ##
1. Melhor compreens�o de `scanf` e `printf` em bases diferentes;
2. Funcionamento do `rand()` e `srand()`
3. Ciclos `switch`, `for` e `if`

## Refer�ncias ##
##### Bibliotecas utilizadas
> stdio.h, time.h, stdlib.h

##### Colegas de apoio
> Diogo Maia, Francisco Freixo

##### Links de apoio
> https://stackoverflow.com/


