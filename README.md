# DesafioPython
Desafio em Python 


01 - QUESTÃO
Dado um array de números inteiros, retorne os índices dos dois números de forma que eles se 
somem a um alvo específico.
Você pode assumir que cada entrada teria exatamente uma solução, e você não pode usar o 
mesmo elemento duas vezes.

Exemplo:

Dado nums = [2, 7, 11, 15], alvo = 9,

Como nums[0] + nums[1] = 2 + 7 = 9,

return [0, 1].


02 – QUESTÃO
Um bracket é considerado qualquer um dos seguintes caracteres: (, ), {, }, [ ou ].
Dois brackets são considerados um par combinado se o bracket de abertura (isto é, (, [ou {) ocorre à esquerda de um 
bracket de fechamento (ou seja,),] ou} do mesmo tipo exato. Existem três tipos de pares de brackets : [], {} e ().
Um par de brackets correspondente não é balanceado se o de abertura e o de fechamento não corresponderem entre 
si. Por exemplo, {[(])} não é balanceado porque o conteúdo entre {e} não é balanceado. O primeiro bracket inclui o 
de abertura, (, e o segundo inclui um bracket de fechamento desbalanceado,].
Dado sequencias de caracteres, determine se cada sequência de brackets é balanceada. Se uma string estiver 
balanceada, retorne SIM. Caso contrário, retorne NAO.

Exemplo:

{[()]} SIM

{[(])} NAO

{{[[(())]]}} SIM


