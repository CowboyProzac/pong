# PONG

Esta é uma recriação do clássico jogo de vídeo pong. Implementado no C
linguagem de programação, usando a biblioteca SDL para exibir gráficos na tela.

Para compilar você precisa ter o SDL instalado em seu sistema e os arquivos de cabeçalho
disponíveis para você sistemas operacionais PATH ambiente variável

	gcc pong.c `sdl2-config --cflags --libs` -o pong

### Atualização 2023

Isto foi portado da versão 1 do SDL para trabalhar com a versão 2 do SDL. Também foi adicionada a capacidade de executar o
executável com o argumento '-f' de linha de comando para rodar em tela cheia 
(irá esticar a imagem 640 * 480 resolução nativa do display de seus sistemas)

Aceitarei qualquer pedido de recursos como atualização da IA ou animação de movimento se houver alguma demanda. Ou 
basta clonar o código e fazer você mesmo. Aproveite!

## Controles
* barra de espaço para iniciar um jogo
* teclas de seta para movimentação
* ESC para sair do jogo

## Imagens
![tela do título](http://i.imgur.com/radat.png)

![jogo de jogo](http://i.imgur.com/CZhqp.png)
