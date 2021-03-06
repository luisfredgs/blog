---
layout: post
title:  "Dicas para aprender Machine Learning"
resume: "O que é preciso para começar a aprender Machine Learning? Eu diria que o principal é que você seja curioso, em primeiro lugar. Depois, alguma afinidade com matemática e programação."
date:   2018-01-18 11:50:00
category: machine-learning
tags: [machine-learning]
permalink: /machine-learning/dicas-para-aprender-machine-learning
status: 0
---
{:.image}
![](/assets/img/dicas-para-aprender-machine-learning.jpg)

O que é preciso para começar a aprender Machine Learning? Uma coisa é certa, você não precisa ser nenhum PhD. Entretando, você precisa ser pelo menos curioso e dedicado. Além disso, ter alguma afinidade com matemática e programação é algo bastante útil, mas não é nada que você não consiga dá conta! 

E não pense que Machine Learning é difícil ou restrito ao pessoal das áreas de ciências exatas, pois essa concepção é extremamente equivocada. No mais, leia o restante deste post para descobrir o quão perto de aprender machine learning você pode está. **[Post com vídeo]**.

Antes de prosseguir, aproveita que já veio aqui e participa do grupo que criei no Telegram, para promover discussões sobre o tema de aprendizagem de máquina e tirar dúvidas: [https://t.me/joinchat/Omx7D1hGjM2K_8YfwwntYw](https://t.me/joinchat/Omx7D1hGjM2K_8YfwwntYw)

No final deste post, espera-se que você saiba:

1. Do que precisa para aprender e praticar Machine Learning sem ter muita dificuldade;

2. Quais livros poderá usar para aprender sobre o assunto;

3. Qual linguagem de programação preciso aprender?

4. Quais ferramentas computacionais são mais usadas?

5. Preciso mesmo aprender tudo isso?

O uso habitual de machine learning é sustentado pela necessidade de modelar, matematicamente, problemas do mundo real utilizando o conhecimento a priori em torno de tais problemas, com a intenção de suportar a tomada de decisões baseado em previsões ou insights sobre ações futuras. 

A ideia é que esse conhecimento a priori esteja contido em massas de dados reunidas ao longo do tempo. Essas massas de dados podem está disponíveis publicamente na internet, nos HD's da empresa para a qual você trabalha, vindas de aplicativos móveis, de sensores, câmeras, enfim.

> *Na maior parte do tempo, Machine Learning representa a necessidade de fazer previsões com base no conhecimento obtido a partir de dados.*

Um algoritmo é normalmente exposto a esse conhecimento, explorando e reconhecendo padrões exaustivamente, com a intenção de obter uma função matemática específica (num amplo espaço de funções possíveis), que seja capaz de usar esses padrões para fazer extrapolações com base em parâmetros que ela nunca viu. 

Essa função é normalmente obtida por meio de um processo de otimização, que testa diferentes soluções até chegar numa que seja robusta o suficiente para fazer boas generalizações com base no conhecimento extraído dos dados pelo tal algorítmo. 

Durante esse processo, vários conceitos matemáticos são utilizados: Álgebra linear, Diferenciação, probabilidade, etc. Contudo, esses conceitos são quase sempre abstraídos pelo uso de bibliotecas e frameworks de machine learning que foram desenvolvidos especialmente para o caso. 

É sempre bom lembrar, entretanto, que o conhecimento desses conceitos matemáticos vai te colocar numa posição vantajosa, uma vez que as bibliotecas de machine learning não fazem tudo sozinhas. 

Às vezes, você precisará expandir os recursos dessas bibliotecas, criando seus próprios modelos e funcionalidades para atender a uma ou outra situação específica. Nessas horas, principalmente, é útil saber como as coisas funcionam para além dos limites da escrita do código. Então, saia da média e não se contente apenas em saber programar. 

Pensando nisso, listarei aqui alguns conceitos que vão te ajudar bastante a praticar Machine Learning sem ter muita dificuldade. Vamos lá....

## Porque a álgebra linear é tão importante para o Machine Learning?

{:.image}
![](/assets/img/linear_algebra.png)
Créditos da imagem: Deep Learning with PyTorch - Eli Stevens

A álgebra linear é uma área da matemática que é largamente utilizada em diversos ramos da engenharia e da ciência. Uma boa compreensão da álgebra linear será imensamente útil se você pretende trabalhar com ML, principalmente na parte de modelagem. Você até pode praticar machine learning sem ter um domínio sequer razoável de álgebra linear, mas algumas coisas não farão muito sentido para você nestas condições.

Não é meu objetivo aprofundar o assunto de álgebra linear neste post, mas se eu puder resumir em poucas palavras no que você deveria se concentrar, a princípio eu diria (a ordem faz diferença): **Escalares**, **Vetores**, **Matrizes** e **Tensores**. Além disso, é importante que você compreenda os seguintes tópicos:

* Multiplicação entre matrizes e vetores

* Matriz identidade e matriz inversa

* Dependência linear

* Transformações lineares

* Autovalores e Autovetores

* Aprenda as notações, como as estruturas são representadas

Aprender sobre as notações será bastante útil se você pretende trabalhar na área de pesquisa, ou se pretende ler papers para pegar algumas ideias. Há outros tópicos, é claro, mas estes são os mais importantes. 

Em machine learning, fazemos um uso intensivo de operações envolvendo os tópicos acima mencionados, sem os quais seria muito difícil trabalhar. É claro que as bibliotecas de código abstraem toda a parte complexa dessas operações, para que você apenas veja o resultado final. Muito provavelmente você vai aprender álgebra linear enquanto estuda e pratica machine learning, aprendendo na prática quais tópicos são verdadeiramente relevantes e quais não são.

## Cálculo diferencial

A diferenciação é uma das mais importantes ferramentas na ciência, como na física, por exemplo, quando estamos tentando modelar a dinâmica de um determinado sistema. Basicamente, as diferenciações relacionam a taxa de variação de uma quantidade específica à outras propriedades presentes no sistema. 

Para citar um exemplo, a dinâmica de um modelo neural em deep learning utiliza diferenciação (derivação parcial) para atualizar os pesos da rede de acordo com alguma regra específica. Um exemplo mais concreto dentro do mesmo contexto seria o algoritmo de retropropagação do erro (backpropagation) que, por meio do *gradiente descendente* da função de perda, utiliza derivadas parciais para atualizar os pesos da rede com base no sinal de erro produzido pelos neurônios na camada de saída. Podemos dizer, na verdade, que a retropropagação é apenas um outro nome que deram para a [regra da cadeia do cálculo](https://pt.wikipedia.org/wiki/Regra_da_cadeia).

> *a dinâmica de um modelo neural em deep learning utiliza diferenciação (derivação parcial) para atualizar os pesos da rede a partir do gradiente descendente da função de perda*

Você pode começar seus estudos em ML sem se ater muito a isso. Contudo, será uma grande vantagem se você tiver um conhecimento pelo menos razoável de:

* Derivadas, bem como as derivadas parciais e regra da cadéia (a derivada fornece a inclinação de uma função $$f(x)$$ num ponto $$x$$, sendo usada pelos algoritmos de otimização para encontrar o "melhor caminho" até um mínimo local, ou um máximo global)

* Derivação com múltiplas variáveis

* Integrais (normalmente apenas as integrais de primeira ordem)

* Cálculo de vetor e função gradiente

{:.image}
![](/assets/img/gradient_descent_2d.png)
O gradiente descendente da função de perda é computado com base nas derivadas parciais da função de perda respectivamente a cada valor peso, sendo utilizado para atualizar os pesos da rede até obter um conjunto de valores que minimize o valor da função.

A figura acima ilustra o uso da derivada por algoritmos de otimização. A visão em 2D é apenas uma simplificação para facilitar o entendimento, visto que, na verdade, a função percorre uma superfície, e a derivada parcial fornece a inclinação da função em cada ponto. Essa inclinação na verdade é uma espécie de "apontamento", que orienta os pesos a "caminharem" na direção de valores que permitam minimizar (ou maximizar) o valor da função custo gradativamente, em pequenos passos. Esse é o papel da derivada em um otimizador, componente importante de muitos algoritmos de machine learning.

Não! Você não vai precisar calcular integrais e derivadas na mão para que seus modelos funcionem. Como já foi dito, tudo isso é abstraído por pacotes de ferramentas que foram desenvolvidas especialmente para o caso. Tudo o que você tem que fazer é usar algumas linhas de código corretamente. 

A mensagem que precisa ser entendida aqui é: Você precisa ao menos saber o que está acontecendo enquanto seu modelo de machine learning está sendo treinado. Esse entendimento influencia na escolha dos hiperparâmetros que vão alterar a dinâmica da aprendizagem do seu modelo, por exemplo. Isso influencia diretamente na qualidade dos modelos. Além disso, ter esse entendimento é útil em situações nas quais você esteja interessado em desenvolver um novo algoritmo de otimização para solucionar um problema específico. Então, conhecimento, nessas horas, é poder!

## Teoria da probabilidade

A incerteza é um conceito chave em inteligência artificial e reconhecimento de padrões. É neste ponto que surge a necessidade de uma ferramenta para quantificar e representar a incerteza. Por tal motivo, a probabilidade é uma ferramenta de grande interesse em ML. Um entendimento básico em teoria da probabilidade é desejável para que você possa trabalhar com os algoritmos e gerar modelos preditivos.

Um exemplo clássico de aplicação da probabilidade em machine learning é o filtro de spam. Qual a probabilidade de um determinado e-mail ser um SPAM? Qual a probabilidade de um cliente ser um bom pagador ou um inadimplente? Frequentemente, a saída do seu modelo será uma distribuição de probabilidades que corresponda às categorias que você está tratando na variável resposta.

## Estatística inferencial

Muita gente não menciona isso. Mas, se você treinou um modelo, viu que acurácia dele estava boa e o aceitou como solução definitiva, provavelmente sua solução está incompleta. Um passo crucial para a aceitação e implantação de um modelo de machine learning em produção é a validação dele. Como saber se um modelo é bom o suficiente para sair da fase de "laboratório"? Quantos modelos você treinou (com diferentes parâmetros)?

Você precisará planejar com cuidado uma série de experimentos, treinar diferentes modelos, testá-los e validá-los estatisticamente (não é só olhar para a acurácia depois de o modelo ter sido treinado). O modelo X é melhor do que o modelo Y? O quanto ele é melhor? O quanto custaria um erro de predição? Para responder a essas questões, você terá que se apoiar em importantes ferramentas da estatística inferencial, tais como os **testes de hipótese**. Qualquer livro de estatística vai te ensinar como conduzir tais testes, fora inúmeros vídeos que se encontram no Youtube. É questão aplicar esses testes no problema em que você está trabalhando.

## Linguagens de programação e outras ferramentas

Não adianta você estudar os conceitos acima e não poder colocar em prática usando uma linguagem de programação. Eu diria que Machine Learning, ao menos na indústria, é 80% usando códigos e 20% aprendendo conceitos teóricos (que fazem muita diferença). Você precisa entender os conceitos, o que é importantíssimo, mas não significa que vai implementar todos os cálculos na unha, isso é impraticável. Você vai precisar de alguma linguagem de programação e frameworks de machine learning.

Se você ainda não programa em nenhuma linguagem, ou pelo menos em nenhuma das que vou listar aqui, então tente começar por aquelas mais valorizadas no mercado. As linguagens de programação mais utilizadas pela comunidade e mais exigidas pelas empresas são:

* **Python**

* **R**

* C++

* Matlab

* Java

* Scala

> *Se você pretende atuar no mercado como profissional destas áreas, então tente buscar conhecimento principalmente em Python ou R, se possível nas duas linguagens*

Hoje em dia, **Python** e **R** são as mais utilizadas, seja por pesquisadores ou por empresas na área de Data Science e IA. Quase não se vê anúncios de vagas exigindo conhecimentos em Matlab, C++, Java ou Scala para atuar na área. Se você pretende atuar no mercado como profissional de Data Science ou Machine Learning, então tente buscar conhecimento principalmente em Python ou R, se possível nas duas linguagens. 

Uma grande maioria das *toolboxes* disponíveis para machine learning — ao menos as que são baseadas em linguagens open source — que existem hoje estão implementadas nestas duas linguagens; a maior parte dos cursos online ou dos livros voltados para este tema se baseiam nestas duas ferramentas. Então, é fundamental que você tente se aprofundar no uso destas linguagens de programação.

Além disso, existem alguns frameworks e libraries que são muito requisitados nas vagas que costumo encontrar no Linkedin, por exemplo. No ecossistema da linguagem Python, posso citar alguns:

* [Tensorflow](tensorflow.org)
* [Pytorch](https://pytorch.org/)
* [Scikit-learn](https://scikit-learn.org/stable/)
* [Pandas](https://pandas.pydata.org/pandas-docs/stable/)
* [Numpy](https://numpy.org/)
* [Scipy](https://www.scipy.org/)

São ferramentas já bastante consolidadas e muito usadas na indústria também. Numpy, por exemplo, possui recursos completos para aplicações de [álgebra linear](https://people.duke.edu/~ccc14/pcfb/numpympl/LinearAlgebra.html); **Pytorch** e **Tensorflow** são bibliotecas especialmente voltadas para a construção de arquiteturas neurais, com o Tensorflow dominando as aplicações em ambientes de produção (até agora); **Scikit-learn** se tornou o toolbox padrão quando o assunto é modelagem usando algoritmos robustos, sem ênfase ao deep learning; **Pandas** é o queridinho durante as análises exploratórias, onde é indispensável o uso de dataframes. Enfim, vale a pena investir tempo em entender o funcionamento dessas ferramentas. Mas não se contente com apenas essas ferramentas, pois há outras inúmeras disponíveis.

Além disso, não podemos esquecer de alguns ambientes voltados para prototipágem e testes de modelos, tais como os [Jupyter Notebooks](https://jupyter.org/). Além disso, a Google te oferece o [Google Colab](https://colab.research.google.com/) com GPU grátis para você já sair brincando sem precisar instalar nada, já que a maioria dos pacotes python para machine learning estão previamente instalados, inclusive as ferramentas citadas acima (você também pode instalar outras libraries facilmente usando o comando "!pip install").

### Quais livros ou cursos online você me recomenda para estudar machine learning?

Por responder essa pergunta, decidi gravar o vídeo abaixo, onde eu indico alguns dos livros que utilizo para estudar. No vídeo eu também apresento um resumo dos pré-requisitos que mencionei nos parágrafos anteriores, bem como algumas dicas sobre onde buscar as informações mais atualizadas sobre o tema.

{:.note}
***ATENÇÃO**: Aos 07:54, eu na verdade estou querendo me referir ao **k-Nearest Neighbors** (o K-NN). Há uma grande diferença em relação ao K-Means, o qual tenta fornecer um agrupamento de dados, com separações bem definidas, baseado na similaridade entre estes dados. Falo mais sobre o K-means [nesse post](https://luisfredgs.github.io/machine-learning/clustering-analysis-an-introduction-to-unsupervised-learning). Peço desculpas pelo equívoco, pois só notei depois de rever o vídeo, logo após ser publicado no canal. Todos os links aos quais me refiro durante a apresentação dos slides estão presentes na descrição do vídeo.*

<div class="video-container">
	<center><iframe width="560" height="315" src="https://www.youtube.com/embed/9aCUXJXPHGw" frameborder="0" allowfullscreen></iframe></center>
</div>

### E se eu não quiser aprender tudo isso para poder usar machine Learning?

As APIs cognitivas da Google (Google Cloud Machine Learning), Microsoft (Azure Machine Learning) e IBM (IBM Watson) existem para facilitar a vida de quem não quer ter o trabalho de estudar tudo o que foi dito nos parágrafos anteriores para poder criar sistemas de inteligência artificial. De fato, se você tiver o conhecimento em programação necessário para utilizar os *endpoits* destas APIs, poderá criar sistemas inteligentes usando modelos prontos e sem se preocupar com teoria. 

Apenas tenha em mente que este uso tem um custo envolvido, pois normalmente estes serviços cobram um valor específico a partir de um determinado volume de requisições. Entretanto, aprender a teoria continua sendo importante se você quiser extrair o máximo do potencial destas APIs e modelar sistemas mais robustos.

### Considerações finais

Tem muito material interessante no Youtube, posts no [Medium](https://medium.com), códigos no Github, competições na [Kaggle](https://kaggle.com) para te ajudar com boas técnicas. O caminho mais rápido é estudar direcionado, algo que alguns treinamentos e cursos online proporcionam. Caso prefira estudar por meio de cursos on-line, não deixe de conferir [meu novo curso na Udemy](https://www.udemy.com/course/processamento-de-linguagem-natural-do-zero-a-producao/?referralCode=58A9E255EE0A65ACF871), onde ensino como criar modelos para processamento de linguagem natural com Tensorflow e Scikit-learn para uso em ambientes de produção.

## Leia também

* [7 livros essenciais para aprender machine learning]({% post_url 2018-10-22-7-livros-essenciais-para-aprender-machine-learning %})

* [Análise de sentimentos com redes neurais recorrentes LSTM]({% post_url 2018-12-23-analise-de-sentimentos-com-redes-neurais-recorrentes-lstm %})

* [Reconhecimento de Entidades Nomeadas (NER) — O que é? Quais são as aplicações?]({% post_url 2017-08-22-reconhecimento-de-entidades-nomeadas-ner-e-aplicacoes %})

* [Classificando textos com Machine Learning]({% post_url 2018-05-07-classificando-textos-com-machine-learning %})

* [Machine Learning: A matemática da aprendizagem supervisionada](https://luisfredgs.github.io/machine-learning/machine-learning-a-matematica-da-aprendizagem-supervisionada)
