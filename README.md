# Freeway Game em Javascript

Este é um projeto que recria o clássico jogo Freeway em Javascript. O objetivo é atravessar a rua com o personagem, que neste caso é uma vaquinha. Ao chegar do outro lado da rodovia, o jogador ganha 1 ponto e retorna à posição inicial. Se o jogador for atingido por algum veículo, perde 1 ponto e também retorna à posição inicial.

O projeto foi desenvolvido para treinar os conhecimentos em Javascript e utiliza as seguintes tecnologias:

- HTML5
- CSS3
- Javascript

## Funcionalidades

- Movimentação do personagem (vaquinha) através das setas do teclado.
- Carros que se movem horizontalmente na rodovia.
- Contagem de pontos ao atravessar com sucesso.
- Redução de pontos ao ser atingido por um veículo.
- Tratativas para evitar que o placar do jogador fique menor do que zero.

## Estrutura do Projeto

A pasta compactada contém os seguintes arquivos e diretórios:

- **Imagens**: Pasta com as imagens utilizadas no jogo, incluindo a imagem da rodovia, dos carros e do personagem (em formato .png).
- **Sons**: Pasta com os sons utilizados no jogo, incluindo o som de colisão (colidiu.mp3), o som de ganhar pontos (pontos.wav) e a trilha sonora (trilha.mp3).
- **Ator.js**: Arquivo que contém as funções relacionadas ao personagem (vaquinha) e à pontuação do jogador.
- **Carro.js**: Arquivo que contém as funções relacionadas aos carros, como velocidade, localização nos eixos X e Y, movimentação, etc.
- **Imagens.js**: Arquivo responsável pelo pré-carregamento das imagens e dos sons utilizados no jogo.
- **p5.collide2d.js**: Biblioteca P5 utilizada para o cálculo de colisões no jogo.
- **Sketch.js**: Arquivo principal que contém a função para desenhar a tela e carregar todas as funções necessárias.
- **Style.css**: Arquivo de estilo CSS que realiza ajustes na página, como o tamanho das bordas.
- **Index.html**: Arquivo de índice que faz as chamadas dos scripts criados.

## Instruções de Uso

1. Clone este repositório em sua máquina local.
2. Abra o arquivo `index.html` em um navegador da web.
3. Use as setas do teclado para movimentar o personagem (vaquinha) e tente atravessar a rua evitando os carros.
4. Ganhe pontos ao chegar do outro lado com sucesso e tome cuidado para não ser atingido pelos carros.
5. Divirta-se!

## Exemplo de Jogo

Você pode ver uma demonstração do jogo em ação [aqui](https://editor.p5js.org/johnmarl0n/full/PeU3XW91a).

## Recursos Utilizados

- [p5.js](https://p5js.org/): Biblioteca JavaScript para criação de gráficos interativos.
- [p5.collide2d](https://github.com/bmoren/p5.collide2D): Biblioteca para detecção de colisão em p5.js.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas (issues) e enviar pull requests para melhorias do jogo.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).
