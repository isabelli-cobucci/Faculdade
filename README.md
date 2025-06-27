 # Funções do R

 - `rm()` -> apaga uma variável;
 - `round()` -> arredonda resultados sem casas decimais;
 - `sqrt()` -> calcula raiz quadrada;
 - `mean() ` -> calcula média;
 - `median()` -> calcula mediana;
 - `min()` -> calcula mínimo;
 - `max()` -> calcula máximo;
 - `var()` -> calcula variância;
 - `sd()` -> calcula desvio padrão;
 - `sum()` -> soma elementos de um vetor;
 - `rexp()`, `rnorm()` -> sorteia aleatoriamente n observações dentro daquela distribuição;
 - `factor()` -> cria um fator. Pode ter como argumentos `levels` (coloca as possibilidades de variáveis),`labels` (muda o nome das variáveis de acordo com a ordem que está escrito em levels) ou `ordered` (diz para função que existe uma ordem e que ela foi estabelecida em levels);
 - `hist()` -> faz um histograma;
 - `table()` -> cria uma tabela de frequência;
 - `view()` -> formata a tabela;
 - `head()` -> apresenta as primeiras linhas de uma tabela;
 - `tail()` -> apresenta as últimas linhas;
 - `barplot()` -> cria um gráfico de barras;
 - `boxplot()` -> cria um boxplot;
 - `pie()` -> cria uma gráfico de setores;
 - `cbind()` -> combina dois quadros de dados;
 - `plot()` -> plota vários tipos de gráficos;
 - `spec()` -> verifica as especificações das variáveis;
 - `sapply()` -> aplica os resultados de uma função em uma lista ou vetor. A primeira variável é o banco de dados, ``function(x)`` é um jeito de criar funções no R.
   ex: `` "sapply(hotels_vienna,function(x) sum(is.na(x)))" ``;
 - `is.na()` -> procura valores ausentes;
 - `seq()` -> faz sequências;
 - `rep()` -> faz sequências com repetições;
 - `sample()` -> sorteia;
 - `matrix()` -> constroi matrizes;
 - `diag()` -> constroi matrizes diagonais;
 - `solve()` -> faz a matriz inversa;
 - `t()` -> acha a matriz transposta;
 - `str()` -> inspeciona o objeto trabalhado;
 - `white.table`-> `x` (é o objeto a ser traballhado), `file`(nome e tipo de arquivo. ex: "csv", "txt", "dat"), `sep`(qual separador decimal. ex:"," ou "."), `dec`(separador de campos. ex:":" ou "\t")

## Anotações de AED
- a função T(Xi) é qualquer uma que se usar para transformar; 
- objetivos das transformações é alterar a forma das distribuições;
- "escala de likert";
- dicionário de variáveis
