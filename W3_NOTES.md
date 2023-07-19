# Week 3: Normal Approximation and Binomial Distribution

This module covers the empirical rule and normal approximation for data, a technique that is used in many statistical procedures. You will also learn about the binomial distribution and the basics of random variables.

**Lernaning Objective**

- Understanding of standardization of data and normal approximation, and why they are important
- Getting familiar with the binomial distribution
- Ability to apply knowledge of standardization, normal approximation and binomial distribution on real data

## The Normal Curve

Nesta aula, são abordados os seguintes tópicos: a regra empírica e a aproximação de norma para dados, a distribuição binomial, ideias básicas sobre variáveis aleatórias e a forma característica do histograma de muitos dados, conhecida como formato de sino. O exemplo apresentado é o histograma das alturas de 928 pais coletados por Sir Francis Galton no século XIX. É mencionado que nem todos os dados seguem essa distribuição normal. Sugestão de literatura para aprofundar o assunto: "Estatística Básica" de Bussab e Morettin.

## The Empirical Rule

A aula explica a regra empírica, que é aplicada quando os dados seguem uma distribuição normal. A regra empírica afirma que cerca de dois terços dos dados ($66,6\%$) estão dentro de um desvio padrão da média, 95% dos dados estão dentro de dois desvios padrão da média e praticamente todos os dados estão dentro de três desvios padrão da média. O texto também mostra como aplicar a regra empírica em um exemplo de medições de altura. Os principais tópicos abordados são a regra empírica, distribuição normal e desvio padrão.

## Standardizing Data and the Standard Normal Curve

A curva normal é determinada pelo valor médio e pelo desvio padrão. Para calcular porcentagens, é necessário padronizar os dados, subtraindo a média e dividindo pelo desvio padrão. O resultado é chamado de valor padronizado ou escore z, que indica quantos desvios padrão a medida está acima ou abaixo da média. Após a padronização, os dados têm média 0 e desvio padrão 1. A curva normal padrão é representada por uma equação, mas não será utilizada neste curso. Os tópicos principais abordados são: curva normal, padronização de dados e escore z.

## Normal Approximation

A aproximação normal significa usar a área sob a curva normal para calcular porcentagens. O exemplo dado é sobre a porcentagem de pais que têm alturas entre 67,4 e 71,9 polegadas. São apresentados quatro passos para a aproximação normal: padronizar os dados, marcar a área no histograma, encontrar a área sombreada sob a curva normal padrão e usar um programa de computador ou tabela para encontrar essa área. No exemplo dado, a área desejada é de 66,8%. Também é mencionado que a regra empírica é um caso especial da aproximação normal.

## Computing Percentiles with the Normal Approximation

O texto discute o uso da aproximação normal para encontrar o percentil 30 de uma distribuição de alturas. O autor explica como encontrar o valor z correspondente ao percentil 30 usando uma tabela ou software e, em seguida, como usar esse valor z para encontrar a altura correspondente. O autor também menciona uma segunda maneira de resolver o problema, usando o valor z para determinar quantos desvios padrão a altura está acima ou abaixo da média. A altura resultante é de 67,4 polegadas.

# Week 3: Binomial Distributions

## The Binomial Setting and Binomial Coefficient

Na aula, o professor discute a probabilidade de ter duas meninas em um grupo de recém-nascidos. Ele usa o conceito de enumeração total para listar todas as possibilidades e, em seguida, usa a regra da adição e a regra da multiplicação para calcular a probabilidade. O professor também introduz o conceito de configuração binomial, onde há repetições independentes de um experimento com dois resultados possíveis (sucesso e falha). Ele menciona a fórmula do coeficiente binomial para calcular o número de maneiras de arranjar sucessos em experimentos. O autor conclui que a fórmula é útil quando o número de possibilidades se torna muito grande.

## The Binomial Formula

A probabilidade de ganhar dois pequenos prêmios em um jogo online é de 30,2%. Isso é calculado usando a fórmula binomial, onde n é igual a 10 (número de experimentos), k é igual a 2 (número de sucessos), a probabilidade de sucesso é de 0,2 e a probabilidade de falha é de 0,8. A fórmula binomial é usada para calcular a probabilidade de um padrão específico de sucessos e falhas em um determinado número de experimentos.

## Random Variables and Probability Histograms

O texto fala sobre a variável aleatória em experimentos binomiais. Ele explica que os resultados dos experimentos são aleatórios e que o número de sucessos é chamado de variável aleatória. A probabilidade de cada resultado pode ser visualizada em um histograma de probabilidade. O texto ressalta que o histograma de probabilidade não está relacionado a dados observados, mas sim a probabilidades teóricas. Os principais tópicos abordados são: variável aleatória, distribuição binomial e histograma de probabilidade.

>Um histograma de probabilidade é uma representação gráfica da distribuição de probabilidade de um conjunto de dados. Ele consiste em uma série de barras, em que cada barra representa um intervalo de valores, e a altura da barra corresponde à probabilidade de observar valores dentro desse intervalo. Em um histograma de probabilidade, o eixo horizontal representa os valores ou intervalos do conjunto de dados, e o eixo vertical representa a densidade de probabilidade ou frequência relativa. A área total sob o histograma é igual a 1, indicando que as probabilidades de todos os valores ou intervalos possíveis somam 1.

How would you define the probability histogram?

Variáveis aleatórias (_random variables_) e histogramas de probabilidade (_probability histograms_) estão interligados e desempenham um papel fundamental na teoria das probabilidades e na estatística. Vamos explorar mais sobre esses conceitos:

**Variáveis Aleatórias:**

Uma variável aleatória é uma função que atribui um valor numérico a cada resultado de um experimento aleatório. Ela representa um fenômeno incerto, cujo valor não é conhecido com certeza antes de ser observado. As variáveis aleatórias podem ser classificadas como discretas ou contínuas.

**Variáveis aleatórias discretas:**

São aquelas que assumem valores isolados ou enumeráveis, geralmente associados a eventos discretos. Exemplos incluem o resultado do lançamento de um dado ou o número de pessoas em uma fila.

**Variáveis aleatórias contínuas:**

São aquelas que podem assumir qualquer valor dentro de um intervalo contínuo. Elas são frequentemente associadas a medidas físicas ou grandezas contínuas, como altura, tempo ou velocidade.

**Histogramas de Probabilidade:**

Um histograma de probabilidade é uma representação gráfica da distribuição de probabilidade de uma variável aleatória. Ele é construído dividindo o intervalo dos valores possíveis em intervalos menores chamados de "bins" ou "classes". A altura de cada barra do histograma representa a probabilidade (ou densidade de probabilidade) associada a cada intervalo.

Para construir um histograma de probabilidade, é necessário coletar dados observados da variável aleatória e contabilizar em quais intervalos os valores se enquadram. Em seguida, a frequência relativa de ocorrência em cada intervalo é calculada e representada como a altura da barra correspondente no histograma.

Histogramas de probabilidade são úteis para visualizar a distribuição de probabilidade de uma variável aleatória. Eles podem revelar informações sobre a forma da distribuição, como a tendência central, dispersão, assimetria e presença de picos ou caudas. Além disso, permitem fazer comparações entre distribuições diferentes e identificar padrões ou comportamentos interessantes nos dados.

**Distribuições de Probabilidade Teóricas:**

Além dos histogramas de probabilidade construídos a partir de dados observados, é possível utilizar distribuições de probabilidade teóricas para descrever o comportamento de variáveis aleatórias. Essas distribuições são definidas matematicamente e fornecem modelos ideais para determinados fenômenos.

Existem várias distribuições teóricas comumente usadas, cada uma com suas próprias propriedades e aplicações. Alguns exemplos incluem a distribuição normal (ou gaussiana), a distribuição binomial, a distribuição de Poisson e a distribuição exponencial.

Ao utilizar uma distribuição de probabilidade teórica, é possível calcular as probabilidades associadas a diferentes valores ou intervalos sem a necessidade de dados observados. Os histogramas de probabilidade podem ser plotados a partir dessas distribuições teóricas para visualizar a distribuição esperada e compará-la com os dados reais.

Em resumo, as variáveis aleatórias desempenham um papel importante na modelagem de eventos incertos, enquanto os histogramas de probabilidade permitem visualizar e compreender a distribuição de probabilidade associada a essas variáveis. As distribuições de probabilidade teóricas fornecem modelos matemáticos que descrevem essas distribuições de forma idealizada.

## Normal Approximation to the Binomial; Sampling Without Replacement

O texto discute a possibilidade de usar a aproximação normal para calcular probabilidades binomiais. Ele mostra que, ao aumentar o número de experimentos, a distribuição binomial se torna mais simétrica e se assemelha a uma curva normal. Em seguida, é explicado como usar a aproximação normal para calcular probabilidades binomiais, através da padronização dos valores. Um exemplo é dado para ilustrar o cálculo da probabilidade de obter no máximo 12 sucessos em 50 tentativas. Por fim, é mencionado que, mesmo em amostragens sem reposição, se a população for muito maior do que a amostra, a aproximação normal ainda pode ser usada.




