# Passa-ou-repassa-IBC
Software para implementar em arduíno do jogo Passa ou Repassa do SBT - Celso Portioli
Descrição: Dois jogadores posicionam-se frente à frente numa mesa retangular. Cada um em uma ponta da mesa. Diante de cada jogador, há um botão cogumelo e um giroled. De um lado da mesa, está o narrador, que faz uma pergunta (do outro lado, onde estão os espetadores, há dois displays próximos a cada jogador, que marca os pontos de cada um, e outro display centralizado, que serve de timer de 10 segundos, com decisegundos e centisegundos).

Então, se um jogador souber a resposta, ele aperta seu botão. Simultaneamente, 
    1. O botão do outro jogador fica impedido de ser acionado por 3 segundos. 
    2. Por 2 segundos, 
        2.1. LED do jogador pisca 5 vezes;
        2.2. Buzina é acionada.

Se o jogador que respondeu à pergunta acertou, então o narrador aperta um botão e sobe 1 unidade no contador de pontos do jogador.

Caso nenhum dos jogadores responda à pergunta, o narrador pode apertar um botão e o timer de 10 segundos é acionado. Ao final do timer (display fica desligado, buzina é acionada por 2 segundos, e se nenhun jogador acertar, ninguém ganha ponto. Próxima pergunta. 

Ademais, há um relógio do lado da mesa do narrador, para que ele veja o tempo que o jogo está durando.
