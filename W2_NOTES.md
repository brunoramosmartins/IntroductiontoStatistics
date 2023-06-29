# Week 2: Producing Data and Sampling

In this module, you will look at the main concepts for sampling and designing experiments. You will learn about curious pitfalls and how to evaluate the effectiveness of such experiments.

**Learning Objectives**

- Understanding the basics of statistical inference, sampling and designing experiments
- Getting familiar with the main pitfalls of sampling
- Ability to apply knowledge and understand real data sampling
- Ability to evaluate the effectiveness of designed experiments

## Introduction

Neste módulo, examinaremos como os dados são produzidos. Veremos os principais conceitos para desenhar amostras e projetar experimentos. Veremos quando é possível atribuir e observar o efeito do tratamento, como um tratamento médico, e quando isso não é possível. Também veremos algumas armadilhas curiosas. Para explicar o que é inferência estatística, vamos olhar para uma pergunta que você provavelmente ouviu muito nas notícias. Qual a porcentagem de eleitores que aprovam a maneira como o presidente dos EUA está lidando com seu trabalho? Este questionamento tem sido feito por empresas de pesquisa desde a década de 1930. Se você pensar sobre isso, é realmente difícil responder a essa pergunta porque você teria que perguntar a cada eleitor, e há mais de 250 milhões de pessoas em idade de votar nos EUA. É uma tarefa assustadora perguntar a todos esses 250 milhões de pessoas. Entretanto, na verdade, não é tão difícil estimar essa porcentagem. O que uma empresa de pesquisa faz é amostrar, digamos, 1 000 eleitores aleatoriamente. Então, usa a porcentagem de aprovação entre esses eleitores como uma estimativa para a porcentagem de aprovação de todos os eleitores.

## Simple Random Sampling and Stratified Random Sampling

Agora, tratamos a importância de uma amostragem aleatória e não tendenciosa na coleta de dados. O autor explica que selecionar uma amostra conveniente, como apenas os eleitores de sua cidade natal, pode introduzir um viés na amostragem, pois os eleitores de diferentes regiões tendem a ter preferências políticas diferentes. O autor também discute os três principais tipos de viés na amostragem: `viés de seleção`, `viés de não resposta` e `viés de resposta voluntária`. Ele sugere que a melhor maneira de evitar esses viéses é usar a chance de alguma forma planejada na amostragem, como na amostragem aleatória simples ou na amostragem estratificada. O autor também menciona que a amostragem estratificada pode resultar em uma estimativa mais precisa, mas é mais complicada de executar. 

Principais tópicos: amostragem aleatória, viés de amostragem, amostragem aleatória simples, amostragem estratificada.

## Bias and Chance Error

O texto aborda a importância de entender os erros em estimativas de amostras aleatórias. Há três partes que compõem uma estimativa: o parâmetro, o erro de amostragem e o viés. 
$$estimate = parameter+bias+chance\ error$$
O erro de amostragem é inevitável, mas pode ser reduzido aumentando o tamanho da amostra. Já o viés é um erro sistemático que não diminui com o aumento do tamanho da amostra e pode ser evitado através do uso de amostragem aleatória. É importante entender esses conceitos para obter estimativas precisas em pesquisas. 

Principais tópicos: amostragem aleatória, erro de amostragem, viés, tamanho da amostra.

**_Literatura sugerida: "Sampling Techniques" de William G. Cochran._**

## Observation vs. Experiment, Confounding, and the Placebo Effect

Nessa parte, abordamos a associação entre o consumo de carne vermelha e o câncer, explicando que essa associação não significa que a carne vermelha cause câncer, pois existem outros fatores que podem influenciar. Para determinar se a carne vermelha causa câncer, é necessário realizar um experimento, no qual um grupo recebe o tratamento (no caso, comer carne vermelha) e outro grupo não recebe. É importante que os grupos sejam semelhantes e que o experimento seja duplo-cego, para evitar vieses. O texto também menciona o efeito placebo e a importância de usar um grupo controle que receba placebo. 
O artigo a seguir se aprofunda na questão do `Placebo`: [The weird power of the placebo effect, explained.](https://www.vox.com/science-and-health/2017/7/7/15792188/placebo-effect-explained)

### Article: The weird power of the placebo effect, explained
### Artigo: O Estranho pode do placebo, explicado

## The Logic of Randomized Controlled Experiments

A importância de um experimento ter uma atribuição aleatória de sujeitos para o grupo de tratamento e controle. Isso é necessário para que quaisquer fatores que possam afetar os resultados sejam igualmente distribuídos entre os grupos. No entanto, é possível que um fator específico seja mais prevalente em um dos grupos, mas isso pode ser calculado e avaliado posteriormente.

## [EXTRA] Industry Insights: Filing a Patent for twoXAR

O texto relata uma conversa entre Andrew e Paul Lee, ex-presidente da Electronic Arts e atual investidor de startups. Andrew contou a Paul sobre um projeto que estava desenvolvendo na área de ciência de dados para encontrar novos tratamentos de drogas e que estava animado para publicar um artigo acadêmico sobre isso. No entanto, Paul questionou se essa era a melhor forma de mudar o mundo e sugeriu que Andrew considerasse criar uma startup e patentear a tecnologia para torná-la acessível ao mundo. Essa conversa fez Andrew repensar seus objetivos e o levou a criar uma nova startup em torno dessa tecnologia. Os principais tópicos abordados são empreendedorismo, inovação e a importância de transformar ideias em ações concretas.

# Week 2: Probability

In this module, you will learn about the definition of probability and the essential rules of probability that you will need for solving both simple and complex challenges. You will also learn about examples of how simple rules of probability are used to create solutions for real-life complex situations.

**Learning Objectives**

- Understanding what probability is and why we use it
- Learning about examples of probability applications in real-life
- Knowing essential rules of probability that help with solving both simple and complex challenges

## The Interpretation of Probability

Neste módulo, discutiremos as regras básicas de probabilidade que precisaremos para nossa metodologia estatística posteriormente. Descobriu-se que existem apenas algumas regras essenciais. Mesmo problemas bastante difíceis em probabilidade podem ser resolvidos aplicando essas poucas regras nos lugares certos. Também veremos alguns estudos de caso que mostram como essas regras simples podem ser usadas de maneiras surpreendentes. Por exemplo, para construir um filtro de spam para e-mail. Então, o que significa falar sobre probabilidade? Vamos olhar para um exemplo de dados. De acordo com o Centro Nacional de Estatísticas de Saúde, em 2015, houve cerca de 4 milhões de bebês nascidos nos EUA e 48,8% desses recém-nascidos eram meninas. Então, se olharmos para um bebê que nasceu em algum dia de 2015 e nos perguntarmos, quais são as chances de que este bebê seja uma menina, diríamos: "Bem, a probabilidade de um bebê ser uma menina é de 48,8%". E escrevemos isso com um P maiúsculo para probabilidade e, entre parentêses, escrevemos o evento que nos interessa. Neste caso, o recém-nascido é uma menina e isso equivale a 48,8%.

$$P(newborn\ is\ a\ girl)=48.8\%.$$

Este exemplo mostra como a probabilidade de um evento é definida. É definido como a proporção de vezes que este evento ocorre em muitas repetições. Portanto, essa definição requer que olhemos para um experimento de chance que possa ser repetido muitas e muitas vezes.

## Complement, Equally Likely Outcomes, Addition, and Multiplication

Nesta aula revisamos as regras básicas para calcular probabilidades, incluindo a regra do complemento, a regra para resultados igualmente prováveis, a regra da adição para eventos mutuamente exclusivos e a regra da multiplicação para eventos independentes. O autor usa exemplos de experimentos de probabilidade, como o nascimento de meninas e meninos e o lançamento de dados, para ilustrar cada regra. É importante lembrar que a regra da adição tem um "ou" e a regra da multiplicação tem um "e", e que as suposições são diferentes para cada uma. A leitura adicional sugerida inclui "Probability: Theory and Examples" de Rick Durrett e "Introduction to Probability" de Joseph K. Blitzstein.

## Four Rules Example: How to Deal with "At Least One"

O texto trata de como calcular a probabilidade de obter pelo menos um seis em três jogadas de um dado. O autor explica que não é possível usar a regra da adição, pois as três jogadas não são mutuamente exclusivas. Em vez disso, ele usa a regra do complemento e a regra da multiplicação para chegar a uma resposta de 41,4%. Os principais tópicos abordados incluem a regra da adição, a regra do complemento e a regra da multiplicação.

## Solving Problems by Total Enumeration

Na aula abordamos a probabilidade condicional usando o exemplo de e-mails de spam e ham. A probabilidade de que a palavra "money" apareça em um e-mail de spam é de 8%, enquanto em um e-mail de ham é de apenas 1%. A probabilidade condicional de B dado A é definida como a probabilidade de A e B dividida pela probabilidade de A. O texto também menciona a regra geral de multiplicação e a regra especial de multiplicação para eventos independentes. Para calcular a probabilidade de que um e-mail aleatório contenha a palavra "money", é necessário introduzir artificialmente o evento de spam ou ham. Usando a regra de adição e a definição de probabilidade condicional, a resposta é de 2,4%. Os principais tópicos abordados são probabilidade condicional, regra geral de multiplicação, regra especial de multiplicação para eventos independentes e cálculo de probabilidade usando a regra de adição.

## Bayes' Rule

Nesta aula, falamos sobre o uso de cálculos de probabilidade para filtros de spam. O professor explica que, para classificar um e-mail como spam, é necessário conhecer a probabilidade de que o e-mail seja spam, dado que a palavra "money" aparece no e-mail. A fórmula para calcular essa probabilidade é conhecida como regra de Bayes. O texto também menciona que, às vezes, é necessário calcular a probabilidade de A, o que pode ser feito usando a fórmula de Bayes expandida. É sugerido que se tente primeiro a versão mais simples da regra de Bayes e, caso não se conheça o denominador, utilizar a versão mais complicada. Além disso, é mencionado que a regra de Bayes transforma probabilidades condicionais de A dado B em probabilidades de B dado A.

## Bayesian Analysis

A aula discute o uso da análise bayesiana para calcular probabilidades. Ele apresenta dois exemplos: o primeiro é sobre classificar e-mails como spam com base em palavras-chave, e o segundo é sobre a probabilidade de uma pessoa ter uma doença com base em um teste positivo. O texto explica como usar a regra de Bayes para atualizar a probabilidade inicial com base em evidências encontradas. No segundo exemplo, é mostrado que mesmo com um teste positivo, a probabilidade da pessoa ter a doença é baixa devido à baixa prevalência da doença na população em geral. Para aprofundar o assunto, sugere-se a leitura de livros sobre estatística bayesiana, como "Bayesian Data Analysis" de Andrew Gelman.

## Warner's Randomized Response Model

O texto discute a dificuldade de obter informações precisas sobre a porcentagem de estudantes que trapacearam em exames universitários devido à possibilidade de os alunos mentirem por vergonha. Para contornar esse problema, é proposta a técnica de randomização, em que os alunos são instruídos a jogar uma moeda antes de responder a uma pergunta sobre trapaça. Ao analisar as respostas coletivamente, é possível estimar a proporção de trapaceiros. A literatura recomendada para aprofundar o assunto é "Randomized Response: A Survey Technique for Eliminating Evasive Answer Bias" de Warner.

## [EXTRA] Industry Insights: Drug Discovery at twoXAR

O texto fala sobre o uso da ciência de dados na descoberta de medicamentos. O autor menciona que muitos esforços nessa área se concentram em examinar um tipo específico de dado ou utilizar metodologias inteligentes para analisar dados existentes. No entanto, o autor defende a importância de utilizar a maior diversidade possível de dados para obter insights mais significativos. O objetivo é identificar tratamentos mais eficazes para doenças, levando em consideração diferentes conjuntos de dados. O autor também menciona a existência de diferentes disciplinas nesse campo, algumas focadas apenas em conhecimento e outras em produzir diagnósticos e medicamentos. Sugestão de literatura: "Data Science in Drug Discovery" de Robert Rallo.