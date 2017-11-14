# Convertingame

>Pedro In�cio a21702545/Xavier Ferreira a21701849


## Descri��o da solu��o
----

	![Fluxograma](fluxograma.svg)

O programa pede o n�mero de perguntas a que o utilizador deseja responder.
Ap�s ter obtido esse valor, o programa pede aleatoriamente uma convers�o de uma base 
(decimal, octal, hexad�cimal) para outra que n�o a mesma (sendo o n�mero
tamb�m aleat�riamente gerado).
O utilizador responde ent�o � pergunta, sendo atribu�do o valor de 
correcta ou errada � resposta.
Ap�s o resultado da pergunta ser mostrado ao utilizador, o programa gera outra pergunta aleatoriamente.
Depois de responder a todas as perguntas, aparece o resultado, que � o n�mero de perguntas acertadas do n�mero total de perguntas.
a que se respondeu correctamente seguido de: *Carrega no Enter para fechar o programa*.


Tivemos alguns problemas com o input quando o programa pede o n�mero de perguntas a serem respondidas e com o input dos n�meros 8 e 9 em perguntas de hexadecimal/decimal para octal: 

Input de n�meros negativos quando o programa pede o n�mero de perguntas a serem respondidadas:
Se o input fosse um n�mero negativo o programa aceitava esse n�mero, mas n�o pode ser feito um n�mero negativo de perguntas.
Este problema foi resolvido ao fazer um _loop do-while_ que faz a pergunta repetidamente at� o input ser um n�mero positivo (indicado nos coment�rios do c�digo).

Input dos n�meros superiores ao da base octal em perguntas de hexadecimal/decimal para octal: 
Se o input fosse um n�mero maior do que a base octal, a pergunta era marcada errada e o programa respondia automaticamente a v�rias perguntas seguidas, sem dar ao utilizador uma oportunidade de responder a essas perguntas.
Este problema foi resolvida ao limpar o input da pergunta, para n�o passar para as outras perguntas e marc�-las como erradas sem o utilizador ter uma oportunidade de responder.

Input de letras quando o programa pede o n�mero de perguntas a serem respondidas:
Se o input for uma letra, essa letra � convertida num n�mero e pede esse n�mero de perguntas para serem respondidas (que costuma ser um n�mero bastante elevado). Tent�mos resolver este problema de v�rias maneiras, mas nenhuma delas funcionou.

### Conclus�o


Este projecto, melhorou bastante a nossa compreens�o do funcionamento de v�rias instru��es em [C](https://en.wikipedia.org/wiki/C_(programming_language)).
Talvez a parte mais dif�cil tenha sido fazer as bases do programa e corrigir os seus erros.
Aprendemos a utilizar [Markdown]( https://guides.github.com/features/mastering-markdown/), a construir fluxogramas e a utilizar de forma correcta instru��es de C como por exemplo o do-while


##### Refer�ncias
* Discuss�o com Nuno Figueiredo sobre "if" e "else"
* Discuss�o com Jo�o Duarte sobre loops em "do-while"
* [https://stackoverflow.com/questions/1406421/press-enter-to-continue-in-c](https://stackoverflow.com/questions/1406421/press-enter-to-continue-in-c)
* [https://codebeautify.org/c-formatter-beautifier](https://codebeautify.org/c-formatter-beautifier)
* [https://guides.github.com/features/mastering-markdown/](https://guides.github.com/features/mastering-markdown/)
* [http://markdownlivepreview.com/](http://markdownlivepreview.com/)