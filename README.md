# *Projeto 3 - Programação de computadores 1*

__*Curso:*__ *ABI - Ciência da computação*

__*Aluno:*__ *João Pedro Amaral Bonfim*

__*Matrícula:*__ *211057600027*

__*Turma:*__ *A*

## *Sobre o projeto*
*Este projeto tem o objetivo a formação da saída de um labirinto dado pelo usuário onde o símbolo @ representa os caminho e # representa a parede por meio da recursividade*

*Poderá ser lido um labirinto de N linhas e M colunas sendo N >= 10 e M <= 100000*
>*__Será utilizada alocação dinâmica, arquivos texto e ponteiros.__*

## *Execução do programa*
*Dentro da pasta zipada `Projeto3_PC1` contém um __Makefile__, para que tudo seja compilado deve-se digitar:*

`make main`

*Agora basta digitar o executável e os 2 arquivos necessários para rodar o programa:*

`./main input.txt output.txt`

*Depois de executar, será lido o labirinto de `input.txt`. Após realizada a busca por profundidade, o caminho será armazenado em `output.txt`.*

### *Exemplo*
*Um exemplo de como deve funcionar:*
>*Arquivo contendo o labirinto e suas dimensões:*
```
10 20
# ##################
#                  #
######### ##########
#           #      #
# ######## ## # ## #
#   #  # # #  #  # #
# ### #  # ## ## # #
# #     #   # #  ###
#   ###   #   ##   #
################## #
```
>*Arquivo de caminho:*
```
#@##################
#@@@@@@@@@         #
#########@##########
#        @@ #@@@   #
# ########@##@#@## #
#   #  # #@# @#@@# #
# ### #  #@##@##@# #
# #     # @@#@# @###
#   ###   #@@@##@@@#
##################@#
```
