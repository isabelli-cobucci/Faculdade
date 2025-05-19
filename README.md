# Funções e atalhos do R

 - `round()` -> arredonda resultados sem casas decimais
 - `ctrl + l` -> limpa console
 - `setas cima e baixo` -> acessa histórico do console
 - `sqrt()` -> calcula raiz quadrada
 - `mean() ` -> calcula média
 - `rm()` -> apaga uma variável
 - `median()` -> calcula mediana
 - `min()` -> calcula mínimo
 - `max()` -> calcula máximo
 - `var()` -> calcula variância
 - `sd()` -> calcula desvio padrão
 - `hist()` -> faz um histograma
 - `rexp()` ou `rnorm()` -> sorteia aleatoriamente n observações dentro daquela distribuição
 - `lm(Y~X, data)` -> nao sei
 - `factor()` -> cria um fator. Pode ter como argumentos `levels` (coloca as possibilidades de variáveis),`labels` (muda o nome das variáveis de a acordo com a ordem que está escrito em levels) ou `ordered` (tem como valor "T" (true) e diz para função que existe uma ordem e que ela foi estabelecida em levels)
 - `table()` -> cria uma tabela de frequência
 - `barplot()` -> cria um gráfico de barras
 - `pie()` -> cria uma gráfico de setores
 - `cbind()` -> combina dois quadros de dados
 - `plot()` -> plot vários tipos de gráficos
 - `view()` -> formata a tabela
 - `head()` -> apresenta as primeiras linhas de uma tabela
 - `boxplot()` -> cria um boxplot
 - `spec()` -> verifica as especificações das variáveis
 - `sapply()` -> aplica os resultados de uma função em uma lista ou vetor. A primeira variável é o banco de dados, ``function(x)`` é um jeito de criar funções no R\.
   ex: `` "sapply(hotels_vienna,function(x) sum(is.na(x)))" ``
 - `sum()` -> soma elementos de um vetor
 - `is.na()` -> procura valores ausentes
 - `seq()` -> seq(from = 1, to = 1, by = ((to - from)/(length.out - 1)),length.out = NULL, along.with = NULL, ...); sequências
 - `rep()` -> rep(x, times = 1, length.out = NA, each = 1); repete
 - `sample()` -> sample(x, size, replace = FALSE, prob = NULL), sorteia


## Anotações de AED
- a função T(Xi) é qualquer uma que se usar para transformar; 
- objetivos das transformações é alterar a forma das distribuições;
- "escala de likert";
- dicionário de variáveis

- 
