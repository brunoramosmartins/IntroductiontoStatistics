# Week 1: Introduction and Descriptive Statistics for Exploring Data

This module provides an overview of the course and a review of the main tools used in descriptive statistics to visualize information.

**Learning Objectives**

- Getting to know the course, the instructor and requirements
- Understanding the basics of descriptive statistics and its tools
- Getting familiar with important principles for visualizing information
- Ability to apply knowledge and understand descriptive statistics of real data

## Introduction

Na introdução discutimos a importância da estatística descritiva na sumarização de dados com números e gráficos. Os principais tópicos abordados incluem os princípios de visualização de informações, a utilidade da estatística descritiva na comunicação de informações e no suporte ao raciocínio sobre dados, e a necessidade de usar amostras para conjuntos de dados grandes. A lição usa o exemplo do acidente do ônibus espacial Challenger para ilustrar a eficácia do uso de gráficos simples para entender dados.

<center>

![](images\\WhyAreDescriptiveStatisticsImportant.png)

</center>

## Pie Chart, Bar Graph, and Histograms

As duas maneiras de resumir dados: resumos numéricos e resumos gráficos. Resumos gráficos são preferidos, pois as pessoas preferem olhar para imagens em vez de números. A escolha da visualização depende da natureza dos dados e do objetivo da visualização. Para dados qualitativos, são usados gráficos de pizza ou gráficos de pontos, enquanto para dados quantitativos, são usados gráficos de barras ou histogramas. Histogramas permitem o uso de uma escala de densidade, que fornece informações sobre lotação e porcentagens. A área de um bloco em um histograma corresponde a uma porcentagem, e a altura do bloco indica quantos sujeitos existem para uma unidade na escala horizontal. O vídeo fornece exemplos de cada tipo de visualização e suas vantagens e desvantagens. 

Literatura sugerida:
1. "The Visual Display of Quantitative Information" de Edward Tufte
2. "Data Visualization: A Practical Introduction" de Kieran Healy.

## Box-and-Whisker Plot and Scatter Plot

O boxplot, uma ferramenta de visualização que mostra cinco números-chave de um conjunto de dados: os números mais baixos e mais altos, a mediana e os quartis primeiro e terceiro. O boxplot é útil para comparar vários conjuntos de dados e pode mostrar tendências nos dados, como a relação entre o número de cilindros em um carro e seu consumo de combustível. A lição também apresenta gráficos de dispersão, que são úteis para visualizar a relação entre duas variáveis. À medida que a educação aumenta, a renda tende a aumentar, e parece haver um aumento acentuado na renda para muitos anos de educação. A lição enfatiza as vantagens de usar visualizações para entender dados.

## Providing Context is Key for Statistical Analyses

Nessa aula distacamos a importância de fornecer contexto em exibições gráficas ao realizar análises estatísticas. O `princípio de pequenos múltiplos` é uma ferramenta útil para esse propósito, pois permite a fácil comparação de dados ao longo do tempo ou em diferentes categorias. A lição fornece exemplos de pequenos múltiplos, incluindo um boxplot de temperaturas registradas em uma estação meteorológica ao longo de 50 anos e um gráfico de séries temporais das taxas de desemprego mensais para cada estado de 1976 a 2009.

### Principle of small multiples (princípio de pequenos múltiplos)

Os princípios de pequenos múltiplos são uma abordagem útil na análise de dados estatísticos, principalmente quando se lida com medidas de dispersão ou variabilidade. Esses princípios fornecem uma maneira de resumir e entender a dispersão dos dados em relação à média.

Existem três princípios de pequenos múltiplos que são comumente utilizados: `o princípio de Chebyshev`, `o princípio de Empirical Rule` (regra empírica) e `o princípio de normalidade`.

**Princípio de Chebyshev:**

O princípio de Chebyshev estabelece que, para qualquer conjunto de dados (seja qual for sua forma de distribuição), pelo menos uma proporção específica de dados estará dentro de um certo número de desvios-padrão da média.
Especificamente, para qualquer número $k$ maior que 1, pelo menos $1 - 1/k^2$ da totalidade dos dados estará dentro de $k$ desvios-padrão da média. Por exemplo, se $k = 2$, então pelo menos $1 - 1/2^2 = 1 - 1/4 = 75\%$ dos dados estarão dentro de 2 desvios-padrão da média.

**Princípio da Regra Empírica:**

A regra empírica, também conhecida como regra 68-95-99.7, é aplicável a distribuições aproximadamente simétricas e em forma de sino, como a distribuição normal.
Segundo a regra empírica, aproximadamente:
68% dos dados estarão dentro de 1 desvio-padrão da média.
95% dos dados estarão dentro de 2 desvios-padrão da média.
99.7% dos dados estarão dentro de 3 desvios-padrão da média.
Esses valores são apenas aproximações e podem variar um pouco em diferentes distribuições.

**Princípio de Normalidade:**

O princípio de normalidade é aplicado quando os dados seguem uma distribuição normal. Nesse caso, os princípios de Chebyshev e a regra empírica se tornam mais precisos.
Para uma distribuição normal, exatamente 68% dos dados estarão dentro de 1 desvio-padrão da média, 95% estarão dentro de 2 desvios-padrão e 99.7% estarão dentro de 3 desvios-padrão.
A distribuição normal é simétrica em torno da média e é caracterizada por sua curva em forma de sino.
Esses princípios são úteis para entender como os dados estão dispersos em relação à média e fornecem informações sobre a probabilidade de um dado ponto de dados estar dentro de um determinado intervalo em relação à média. No entanto, é importante ter em mente que esses princípios são aproximações e podem não ser precisos para todas as distribuições de dados.

## Pitfalls when Visualizing Information

Nessa aula discutimos a tentação de criar gráficos chamativos ao projetar com software moderno, mas como isso pode resultar em resultados ruins. O exemplo de um gráfico de barras tridimensional comparando doações anuais a três universidades é usado para ilustrar a dificuldade em comparar números ao usar gráficos chamativos. A lição sugere que um gráfico de pontos teria sido uma opção melhor para exibir esses dados. A lição também faz referência à apresentação em PowerPoint de Gettysburg por Peter Norvig como um exemplo dos possíveis problemas ao usar gráficos chamativos.

## Mean and Median

A lição em vídeo discute medidas resumidas numéricas, especificamente a média e a mediana, e como elas podem ser usadas para resumir dados. A _mean_ é a média, enquanto a mediana é o ponto médio onde metade dos dados é maior e metade é menor. Se um histograma é simétrico, a média e a mediana são iguais, mas se ele é assimétrico, a mediana é uma medida melhor. A lição também introduz percentis, como o percentil 90 e 75, que podem ser usados para entender a distribuição de renda. Os principais tópicos abordados são média, mediana, assimetria, percentis e quartis. Para aprofundar o assunto, pode-se consultar "Estatística para Negócios e Economia" de Anderson, Sweeney e Williams.

## Percentiles, the Five Number Summary, and Standard Deviation

O texto trata de medidas de resumo de dados estatísticos. O boxplot é apresentado como uma forma de visualização dos dados, mostrando cinco números: o menor valor, o primeiro quartil, a mediana, o terceiro quartil e o maior valor. A distância entre o terceiro e o primeiro quartil é chamada de intervalo interquartil e é uma medida de dispersão dos dados. No entanto, é mais comum usar o desvio padrão como medida de dispersão. A fórmula para o desvio padrão é apresentada, mas é enfatizado que não é necessário memorizá-la, já que calculadoras e computadores podem fazê-lo. O desvio padrão é uma medida de dispersão que leva em conta a diferença de cada número em relação à média, eleva essa diferença ao quadrado, calcula a média desses quadrados e, finalmente, tira a raiz quadrada. A média e o desvio padrão são frequentemente usados para resumir dados, mas podem ser sensíveis a valores extremos. Nesses casos, é melhor usar a mediana e o intervalo interquartil. 

Principais tópicos: boxplot, medidas de resumo, desvio padrão, média, mediana, intervalo interquartil.

Para aprofundar o assunto, sugere-se a leitura do livro "Estatística Básica" de Bussab e Morettin.

<center>

![](images\\thestandarddeviation.png)

</center>

## [EXTRA] Industry Insight: Introduction to Andrew Radin

Andrew Radin, CEO e co-fundador da twoXAR, discute sua formação em ciência da computação e seu interesse em causas sociais. Ele explica como sua esposa o encorajou a usar suas habilidades em ciência de dados para ter um impacto significativo no mundo, levando-o a fazer um curso em Stanford na área de bioinformática. Durante o curso, ele foi inspirado por uma palestra sobre o uso da expressão gênica e da expressão diferencial para descobrir novos medicamentos potenciais. Isso, combinado com seu trabalho anterior na incorporação de conjuntos de dados diversos, levou à gênese de seu projeto e, finalmente, à tecnologia por trás da twoXAR. A empresa usa inteligência artificial para descoberta de medicamentos. A literatura para aprofundar o assunto pode incluir artigos sobre o uso de IA na descoberta de medicamentos e a importância da incorporação de conjuntos de dados diversos.