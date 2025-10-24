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
 - `cumsum()` -> retorna um vetor com a soma cumulativa; 
 - `factor()` -> cria um fator. Pode ter como argumentos `levels` (coloca as possibilidades de variáveis),`labels` (muda o nome das variáveis de acordo com a ordem que está escrito em levels) ou `ordered` (diz para função que existe uma ordem e que ela foi estabelecida em levels);

## Família Apply

- `apply()` -> aplica uma função a cada elemento de uma linha ou colunas de uma matriz, array ou data frame.
- `lapply()` -> aplica uma função a cada elemento de uma linha ou coluna de um vetor, lista ou data frame. a saída é uma lista. 
- `sapply()` -> aplica uma função a cada elemento de uma linha ou coluna de uma lista, vetor ou data frame. tenta simplificar a saída. se `simplify` for TRUE a saída é vetor, se FALSE a saída é lista. 
- `tapply()` -> aplica uma função a estratos de um vetor, lista ou data frame usando um fator para definir os grupos. usa `simplify` também.
- `by()` -> aplica uma função a estratos de um data frame ou matriz. é estratificado por um *fator*.
- `do.call()` -> executa uma função cujos argumentos estão em uma lista. 
- `aggregate()` -> aplica função a estratos de um dataframe
- `mapply()` -> Função é aplicada sobre o 1º elemento de cada um dos argumentos, em seguida ao 2º, etc. argumentos podem ser listas ou vetores. saída é um vetor ou matriz. usado para múltiplas entradas. 

## Tabelas
   
 - `table()` -> cria uma tabela de frequência;
 - `view()` -> formata a tabela;
 - `head()` -> apresenta as primeiras linhas de uma tabela;
 - `tail()` -> apresenta as últimas linhas;
 - `cbind()` -> combina dois quadros de dados por coluna;

## Gráficos

### Funções High Level
 - `hist()` -> faz um histograma;
 - `barplot()` -> cria um gráfico de barras;
 - `boxplot()` -> cria um boxplot;
 - `pie()` -> cria uma gráfico de setores;
 - `plot()` -> plota vários tipos de gráficos;

### Funções Low Level
 - `plot()` -> plota vários tipos de gráficos;
 - `lines()` -> adiciona linha ao gráfico existente;
 - `text()` -> adiciona texto ao gráfico existente;
 - `legend()` -> adicona uma legenda ao gráfico existente;
 - `arrow()` -> adiciona uma seta ao gráfico existente;

## Manipulação de variáveis

 - `str()` -> inspeciona o objeto trabalhado;
 - `spec()` -> verifica as especificações das variáveis;
 - `summary()` -> da o resumo dos 5 números;
 - `sapply()` -> aplica os resultados de uma função em uma lista ou vetor. A primeira variável é o banco de dados, ``function(x)`` é um jeito de criar funções no R.
   ex: `` "sapply(hotels_vienna,function(x) sum(is.na(x)))" ``;
 - `is.na()` -> procura valores ausentes;
 - `seq()` -> faz sequências;
 - `rep()` -> faz sequências com repetições. o argumento `each` repete cada elemento x vezes, já o `times` repete a sequência x vezes;
 - `replicate()` -> repete o comando x vezes;
 - `sample()` -> sorteia;
 - `sort()` -> ordena vetores;
 - `order()` -> da a ordem (crescente ou decrescente) que cada número deve ficar de acordo com os índices de posição no vetor. ex: vetor(5, -5, 3, 0) terá saída (2, 4, 3, 1);
 - `rank()` ->  da a ordem (crescente ou decrescente) que cada número deve ficar de acordo com a posição que cada vetor ficaria em ordem. ex: vetor(5, -5, 3, 0) terá saída (4, 1, 3, 2);
 - `with()` -> com um conjunto de dados faça alguma coisa;
 - `lapply()` -> aplica a função ao objeto;
 - `unique()` -> retorna o vetor sem repetições;

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
-  `Links`:
   * [texto] e (link) ou <"link">;
-  `Pacotes de cores`: R Color Brewer, Viridis, Wes Anderson
-  site lupercio : https://bessegato.github.io/

