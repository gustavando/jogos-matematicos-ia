# Jogo Soma 10

## Histórico

Houve uma tentativa inicial de solicitar o jogo "aos poucos" para o Gemini. Comecei descrevendo o que eu queria em uma rodada - a ideia central do jogo. Depois fui solicitei a pontuação, depois o conceito de "partida", depois a duração da partida com tempo definido.

Cheguei a um ponto em que muita coisa não funcionava como esperado, e não conseguia mais avançar. Então, decidi abandonar o código já feito e começar novamente.

Nesse momento, usei o prompt a seguir. Com esse único prompt o jogo ficou praticamente pronto, e fiz apenas algumas solicitações de ajustes de alguns detalhes visuais.

## Prompt principal

Vamos usar um pouco do que você já aprendeu, e vou dizer novamente, do início, o que é para ser feito.

Nosso jogo, o "Jogo soma 10", tem o conceito de "partida". Cada partida é composta de uma ou mais "rodadas".

A cada rodada, vamos ter o "número principal", variando de 1 a 9, e três opções de escolha, variando também de 1 a 9. As opções de escolha em uma rodada não podem se repetir. A opção de escolha correta é aquela que, somada ao número principal, resulta em 10.

Temos a "pontuação" que inicia sempre com o valor 0. A cada vez que o usuário acertar a escolha correta, deve ser adicionado 1 ao valor da pontuação, ou seja, pontuação = pontuação + 1.

A cada vez que o usuário errar a escolha, a pontuação permanece inalterada.

Quando o usuário fizer sua escolha, o jogo deve informar se ele acertou ou errou. Se acertou, informar a soma resultando em 10, no formato: `<número principal> + <escolha correta> = 10`. Se ele errou, informar o resultado da escolha que ele fez, no formato `<número principal> + <escolha feita> = <valor da soma>`, e indicar também qual teria sido o valor correspondente à escolha correta.

Depois de informar isso, o jogo passa para a próxima rodada, onde o processo se repete.

A partida deve durar 30 segundos, começando a contar ao iniciar a primeira rodada. Ao fim dos 30 segundos, a rodada atual deve ser interrompida, e não vai interferir na pontuação. Nesse momento, o jogo deve informar o fim da partida, e mostrar a pontuação da partida ao jogar, e dar a ele a opção de começar uma nova partida.