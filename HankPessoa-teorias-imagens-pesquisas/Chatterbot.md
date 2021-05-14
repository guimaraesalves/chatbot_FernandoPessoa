# Chatterbot

https://chatterbot.readthedocs.io/en/stable

## Sobre o Chatterbot

<hr>

ChatterBot é uma biblioteca Python que facilita a geração de respostas automatizadas para a entrada de um usuário. O ChatterBot usa uma seleção de algoritmos de aprendizado de máquina para produzir diferentes tipos de respostas. Isso torna mais fácil para os desenvolvedores criar bots de bate-papo e automatizar conversas com os usuários. Para obter mais detalhes sobre as ideias e conceitos por trás do ChatterBot, consulte o diagrama de fluxo do processo.

Um exemplo de entrada típica seria algo assim:

> **usuário:** Bom dia! Como você está? 
>
> **bot:** Estou muito bem, obrigado por perguntar.
>
> **usuário:** De nada. 
>
> **bot:** Você gosta de chapéus?

## Independência da Língua

<hr>

O design independente de idioma do ChatterBot permite que ele seja treinado para falar qualquer idioma. Além disso, a natureza do aprendizado de máquina do ChatterBot permite que uma instância de agente melhore seu próprio conhecimento de possíveis respostas à medida que interage com humanos e outras fontes de dados informativos.

## Como funciona o ChatterBot?

<hr>

Uma instância destreinada de Chatterbot começa sem conhecimento de como se comunicar. Cada vez que um usuário entra em uma declaração, a biblioteca salva o texto que eles inseriram e o texto que a declaração estava em resposta a. 

Como Chatterbot recebe mais informações, o número de respostas que ela pode responder e a precisão de cada resposta em relação ao aumento da instrução de entrada. O programa seleciona a resposta correspondente mais próxima, procurando a demonstração conhecida correspondente mais próxima que corresponde à entrada, ele escolhe uma resposta da seleção de respostas conhecidas a essa declaração.

## Process flow diagram

<hr>

![ChatterBot process flow diagram](https://chatterbot.readthedocs.io/en/stable/_images/chatterbot-process-flow.svg)



> **Get Input**
> Obtenha informações de alguma fonte
> (console, API, reconhecimento de voz, etc.)

> **Process Input**
> A instrução de entrada é processada por cada um dos adaptadores lógicos.

> **Logic Adapter 1**
>
> 1. Selecione uma declaração conhecida que mais se assemelhe à declaração de entrada
> 2. Retorne uma resposta conhecida para a correspondência selecionada e um valor de confiança com base na correspondência

> **Logic Adapter 2** 
>
> 1. Selecione uma declaração conhecida que mais se assemelhe à declaração de entrada 
> 2. Retorne uma resposta conhecida para a correspondência selecionada e um valor de confiança com base na correspondência

>  Retorne a resposta do adaptador lógico que gerou o maior valor de confiança para seu resultado

> **Return response**
> Retorne a resposta para a entrada
> (console, API, síntese de voz, etc)

