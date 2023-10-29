# Observações sobre o desafio "Classificador de Nível de Herói"


## 1
Na estrutura de decisão, há uma parte que deixa em dúvida como decidir o nível:

Se XP for menor do que 1.000 = Ferro
Se XP for entre 1.001 e 2.000 = Bronze

Veja que o valor de XP 1000 ficou sem um retorno, pois a categoria Ferro só aceita números de 0 a 999 (considerando que não há xp negativa)
Veja também que a categoria Bronze só aceita valores de 1001 a 2000

Nesse caso, para concluir o desafio, eu tomei a decisão de colocar a categoria Ferro de 0 a 1000, atualizando o texto para o seguinte:

Se XP for menor ou igual a 1.000 = Ferro

Isso corrigiu a primeira parte do problema.


## 2
O segundo problema também se trata de um problema na estrutura de decisão:

Se XP for entre 2.001 e 5.000 = Prata
Se XP for entre 6.001 e 7.000 = Ouro

Veja que é um problema parecido com o anterior, onde deixa todos os valores de 5001 a 6000 sem categoria.

Nesse caso, para concluir o desafio, eu tomei a decisão de colocar a categoria Ouro de 5001 a 7000, atualizando o texto para o seguinte:

Se XP for entre 2.001 e 5.000 = Prata
Se XP for entre 5.001 e 7.000 = Ouro

Com isso, pude prosseguir com a solução do desafio.