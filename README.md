 # Funções do R

 - `rm()` -> apaga uma variável;
 - `round()` -> arredonda resultados sem casas decimais;

## Funções Básicas
  
 - `sqrt()` -> calcula raiz quadrada;
 - `mean() ` -> calcula média;
 - `median()` -> calcula mediana;
 - `min()` -> calcula mínimo;
 - `max()` -> calcula máximo;
 - `var()` -> calcula variância;
 - `sd()` -> calcula desvio padrão;
 - `sum()` -> soma elementos de um vetor;
 - `quantile()` -> faz intervalo de confiança;
 
 - `factor()` -> cria um fator. Pode ter como argumentos `levels` (coloca as possibilidades de variáveis),`labels` (muda o nome das variáveis de acordo com a ordem que está escrito em levels) ou `ordered` (diz para função que existe uma ordem e que ela foi estabelecida em levels);

## Tabelas
   
 - `table()` -> cria uma tabela de frequência;
 - `view()` -> formata a tabela;
 - `head()` -> apresenta as primeiras linhas de uma tabela;
 - `tail()` -> apresenta as últimas linhas;
 - `cbind()` -> combina dois quadros de dados por coluna;

## Gráficos

- `hist()` -> faz um histograma;
 - `barplot()` -> cria um gráfico de barras;
 - `boxplot()` -> cria um boxplot;
 - `pie()` -> cria uma gráfico de setores;
 - `plot()` -> plota vários tipos de gráficos;
 - `lines()`
 - `text()`

## Manipulação de variáveis

 - `str()` -> inspeciona o objeto trabalhado;
 - `spec()` -> verifica as especificações das variáveis;
 - `summary()` -> da o resumo dos 5 números;
 - `sapply()` -> aplica os resultados de uma função em uma lista ou vetor. A primeira variável é o banco de dados, ``function(x)`` é um jeito de criar funções no R.
   ex: `` "sapply(hotels_vienna,function(x) sum(is.na(x)))" ``;
 - `is.na()` -> procura valores ausentes;
 - `seq()` -> faz sequências;
 - `rep()` -> faz sequências com repetições;
 - `replicate()` -> repete o comando x vezes;
 - `sample()` -> sorteia;
 - `sort()` -> ordena vetores;
 - `order()` -> da a ordem (crescente ou decrescente) que cada número deve ficar de acordo com os índices de posição no vetor. ex: vetor(5, -5, 3, 0) terá saída (2, 4, 3, 1);
 - `rank()` ->  da a ordem (crescente ou decrescente) que cada número deve ficar de acordo com a posição que cada vetor ficaria em ordem. ex: vetor(5, -5, 3, 0) terá saída (4, 1, 3, 2);
 - `with()` -> com um conjunto de dados faça alguma coisa;

## Matrizes

 - `matrix()` -> constroi matrizes;
 - `diag()` -> constroi matrizes diagonais;
 - `solve()` -> faz a matriz inversa;
 - `t()` -> acha a matriz transposta;
 - `white.table()`-> `x` (é o objeto a ser traballhado), `file`(nome e tipo de arquivo. ex: "csv", "txt", "dat"), `sep`(qual separador decimal. ex:"," ou "."), `dec`(separador de campos. ex:":" ou "\t");

## Importação e exportação de dados

 - `getwd()` -> dá o caminho dos arquivos;
 - `setwd()` -> muda o caminho dos arquivos;
 - `read.table()`-> importa dados, tem variações;
 - `source()` -> executa código R de um arquivo ou conexão;

## Distribuições de probabilidade

 - `choose()` -> calcula combinação;
 - `lm()` -> calcula os valores para o modelo linear;
 - `d+nomedadistribuiçaõ()` -> funçao densidade de probabillidade;
 - `p+nomedadistribuição()` -> função de probabilidade acumulada;
 - `q+nomedadistribuição()` -> função quantílica, a inversa da acumulada;
 - `r+nomedadistribuição()` -> sorteia aleatoriamente n observações dentro daquela distribuição;

## Anotações R Studio

-  `include`: Valores são computados porém não temos a saída (output) nem o chunk mostrado no relatório.
-  `eval`: Valores não são computados e não temos a saída, porém o chunk é mostrado no relatório. 
-  `echo`: Valores são computados e temos a saída, porém o chunk não é mostrado no relatório.
-  `Pacotes de cores`: R Color Brewer, Viridis, Wes Anderson
-  site lupercio : https://bessegato.github.io/

## Anotações de AED
- a função T(Xi) é qualquer uma que se usar para transformar; 
- objetivos das transformações é alterar a forma das distribuições;
- "escala de likert";
- dicionário de variáveis
