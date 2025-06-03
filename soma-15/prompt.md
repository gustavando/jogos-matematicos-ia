# Jogo Soma 15

## Histórico

A partir do chat onde foi gerado o Jogo Soma 10, eu solicitei a criação desse novo jogo.

## Prompt principal

Quero fazer um novo jogo a partir desse, com o mesmo funcionamento em relação a partida, rodadas, número principal, opções, pontuação e tempo de duração.

A única diferença é que a opção de escolha correta é aquela que, somada ao número principal, resulta em 15.

### Comentários a respeito

Foi interessante como o Gemini identificou que o "número principal" não poderia mais ser qualquer número de 1 a 9, pois os números de 1 a 5 não combinariam com nenhum outro de 1 a 9 para somar 15. Então, ele decidiu fazer com que o número principal variasse somente de 6 a 9.

## Prompts de ajuste posteriores

### Evitar a repetição do número principal

Faça o seguinte ajuste: o número principal escolhido para uma rodada nunca deve ser igual ao número principal da rodada imediatamente anterior. Por exemplo: se na rodada 1 o número principal foi "6", na rodada 2 o número principal não pode ser "6".

### Ajuste nos elementos mostrados na tela de fim de jogo

Quero um ajuste: remover alguns elementos da tela de "Fim de Jogo". Logo após a linha que mostra o "tempo restante: 0 segundos", está o quadro onde aparece o "número principal" nas rodadas. Quero que esse quadro seja removido desta tela. Logo após esse quadro, estão os três controles onde aparecem as opções de escolha nas rodadas. Quero que eles sejam removidos também dessa tela.