![matrix](Matrix_Pilulas.png)



# Capítulo 10 - Machine Learning - DSA

## 10.1 - Introdução a Machine Learning
<hr>

## 10.2 - O que é Aprendizado de Máquina?
<hr>


### Conceitos de Aprendizagem

>Koogan/Houaiss:
"Aprendizagem-Ação de aprender..."
"Aprender- adquirir o conhecimento de, ficar sabendo, instruir-se ..."
<p>

Aprendizado é a capacidade de se adaptar, modificar e melhorar seu comportamento e suas respostas, sendo uma das propriedades mais importantes dos seres ditos inteligentes, sejam eles humanos ou não.
<p>

"...psicol.-Método que consiste em estabelecer conexões entre certos estímulos e determinadas respostas, cujo resultado é aumentar a adaptação do ser ao seu ambiente"
<p>
"Aprendizagem é o processo cognitivo que se estabelece entre o organismo e os estímulos emitidos pelo meio ambiente. 
Assimilação de informações: aprendizado."
Filme: O Enigma de Kaspar Hauser".
<p>
<p>

**Adaptação** >> **Correção** >> **Otimização** >> **Representação** >> **Interação**

* <u>Adptação:</u> Mudança de comportamento de forma a evoluir, melhorar segundo algum critério;
* <u>Correção:</u> Correção dos erros cometidos no passado, de modo a não repeti-los no futuro;
* <u>Otimização:</u> A melhoria da performance do sistema como um todo, implica numa mudança do comportamento do sistema buscando uma melhoria;
* <u>Representação:</u> Uma forma de representar este conhecimento. Uma maneira de guardar conhecimento em regras gerais;

* <u>Interação:</u> Trocar experiência com o meio que o cerca para adquirir novos conhecimentos.



**__Estamos tentando reproduzir o processo de aprendizado de seres humanos em máquinas, através de algoritmos de Machine Learning.__**

## 10.3 - O que é Aprendizado de Máquinas?
<hr>

Machine Learning é Matemática, Estatística e Programação de Computadores!

> Machine Learning é um subcampo da Inteligência Artificial. É o estudo e construção de algoritmos que podem aprender a partir de dados e fazer previsões. O aspecto iterativo do aprendizado de máquina é  importante porque, conforme os modelos são expostos a novos dados, eles são capazes de se adaptar de forma independente.



> Machine Learning ou Aprendizado de Máquina é um metódo de análise de dados que automatiza o desenvolvimento de modelos analíticos. Usando algoritmos que aprendem iterativamente a partir de dados, o aprendizado de máquina permite que os computadores encontrem insights através do reconhecimento de padrões.



##  10.4 - Inteligência Artificial x Machine Learning x Deep Learning.
<hr>

<img src="https://miro.medium.com/max/1634/0*iqMgyPf5WToHHoS6.png" alt="Deep Learning: do Conceito às Aplicações | by Marlesson Santana | Data  Hackers | Medium" style="zoom: 50%;" />

**Machine Learning é um subconjunto da Inteligência Artificial**

Dentro de Machine Learning temos vários algoritmos.

Dentre estes algoritmos temos uma categoria de destaque:

**Deep Learning**

_Conjunto de redes neurais artificiais_



## 10.5 - Tipos de Aprendizagem de Máquina
<hr>

* Aprendizado de Máquina:
  * Aprendizagem Supervisionada;
    * Previsão de valores ou classes;
    * Os dados de treino precisam conter os valores de entrada e saída, para que o modelo aprenda como, a partir de novos dados de entrada, gerar a saída correta.
  * Aprendizagem Não Supervisionada;
    * Identificação de grupos (clusters) de dados;
    * Os dados de treino contém apenas entrada;
  * Aprendizagem Por Reforço;



Aprendizagem Supervisionada		| Aprendizagem não Supervisionada 
:------------		| :------------
Previsão de valores ou classes;	| Identificação de grupos (clusters) de dados; 
Os dados de treino precisam conter os valores de entrada e saída, para que o modelo aprenda como, a partir de novos dados de entrada, gerar a saída correta.	| Os dados de treino contém apenas entrada; 



## 10.6 - Aprendizagem Supervionada - Parte 1/2

## 10.7- Aprendizagem Supervionada - Parte 2/2

<hr>

O Algoritmo aprende a partir dos Dados de exemplo, (dados de entrada) e possíveis resultados (dados de saída), podendo ser valores quantitativos e valores qualitativos. A fim de prever a resposta correta quando recebe novos conjuntos de dados.

Semelhante a abordagem Humana mediante a supervisão de um professor.

![aprendizagemMaquina](/home/mateus/Documentos/HankPessoa-teorias-imagens-pesquisas/aprendizagemMaquina.png)



**Exemplo**

Atributos (tamanho, números de quartos, ano de constução) = __dados de entrada__ - _Input_

Preço da Casa = __dados de saída__ - _Output_



A **Aprendizagem supervisionada** se divide em duas categorias:

* **Classificação**: tem como alvo variáveis Qualitativas (categoricas), pegando a entrada e atribuindo uma classe, categoria.

  Ex.: "sim" ou "não", Mapeamento de uma imagem facial, é masculino ou feminino?

  Se forem duas 2 opções --> binária (2 classes)

  Se forem mais de duas opções --> Classificação Multiclasses

* **Regressão**: O alvo é um valor numérico, valor diferente de um booleano.

  EX.: Quanto custa? Quantos existem?

###  Aprendizagem Supervisionada 

É o termo usado sempre que o programa é "treinado" sobre um conjunto de dados pré-definido.

Os algoritmos de aprendizado supervisionado fazem previsões com base em um conjunto de exemplos. Dados históricos de uma ação na bolsa (exemplo);

Análise de Sentimentos é um tipo de classificação, ou seja, aprendizagem supervisionada.

é usada em aplicações aonde dados históricos preveem eventos futuros;



## 10.8 - Aprendizagem Não Supervisionada

<hr>

O **Algoritmo** aprende com os dados de entrada mas sem qualquer resposta associada;

Alguns sistemas de recomendação que você encontra na internet sob a forma de automação de marketing são baseados neste tipo de aprendizagem. (algoritmo de automação)

não dizemos ao algoritmo qual é a resposta certa ele as infere através dos dados de entrada e detecta padrões.

O aprendizado não supervisionado é usado com dados que não possuem rótulos históricos, ou seja, nós não temos variáveis target (as variáveis de saída) para serem estimadas.

O objetivo é explorar os dados e encontrar algum rótulo neles.

técnicas mais populares: Mapas auto-organizáveis, agrupamentos e decomposição em valores;



## 10.9 - Treinamento, Validação e Teste

O processo de aprendizagem dos algoritmos de Machine Learn começa com a criação de subsets dos seus dados, são os chamados dados de treino e dados de teste.

![treinamento-validacao-teste](/home/mateus/Documentos/HankPessoa-teorias-imagens-pesquisas/treinamento-validacao-teste.png)



* A divisão comum é de:

  * 75 a 70% -  dados de treino;
  * 20% - dados de validação;
  * 10% - dados de teste;

  é recomendável realizar a separação de forma aleatória, independente da ordenação inicial dos dados.

## 10.10 - Cross-Validation.

![](/home/mateus/Documentos/HankPessoa-teorias-imagens-pesquisas/crossValidation01.png)





![crossValidation02](/home/mateus/Documentos/HankPessoa-teorias-imagens-pesquisas/crossValidation02.png)





## 10.11 - O que é um modelo preditivo?

![modeloPreditivo01](/home/mateus/Documentos/HankPessoa-teorias-imagens-pesquisas/modeloPreditivo01.png)



**Etapas Repetidas em ciclos: **

* Coleta de Dados.

* Exploração e Preparação.

* Treinamento do Modelo.

  O processo de "fit" do modelo a um dataset é chamado de treinamento do modelo.

* Avaliação do Modelo.

* Otimização do Modelo.

![](/home/mateus/Documentos/HankPessoa-teorias-imagens-pesquisas/modeloPreditivo02.png)



## 10.12 - Modelo Preditivo Um Pouco de Matemática



































