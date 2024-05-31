# 1. SNAKE GAME


Este é um simples jogo de Snake (cobrinha) desenvolvido em Python utilizando a biblioteca Pygame. O objetivo do jogo é controlar a cobra para coletar comida, fazendo-a crescer em tamanho sem colidir com as bordas ou com o próprio corpo.

## Requisitos

- Python 3.x
- Pygame



## Como Jogar

1. Execute o jogo:
    ```sh
    python snake_game.py
    ```

2. Controle a cobra utilizando as teclas de seta:
    - **Seta para cima**: Move para cima
    - **Seta para baixo**: Move para baixo
    - **Seta para esquerda**: Move para esquerda
    - **Seta para direita**: Move para direita

3. Colete a comida (quadrado verde) para ganhar pontos e aumentar o tamanho da cobra.

4. Evite colidir com as bordas da tela e com o próprio corpo da cobra. Caso contrário, o jogo terminará.

## Estrutura do Código

- `largura` e `altura`: Define o tamanho da tela do jogo.
- `tamanho_quadrado`: Define o tamanho de cada segmento da cobra e da comida.
- `velocidade_jogo`: Define a velocidade do jogo (número de frames por segundo).
- `gerar_comida()`: Gera uma nova posição para a comida.
- `desenhar_cobra(tamanho, pixels)`: Desenha a cobra na tela.
- `desenhar_pontuacao(pontuacao)`: Mostra a pontuação atual na tela.
- `desenhar_comida(tamanho, comida_x, comida_y)`: Desenha a comida na tela.
- `selecionar_velocidade(tecla)`: Define a nova direção da cobra com base na tecla pressionada.
- `rodar_jogo()`: Função principal que executa o loop do jogo.

# Capturas de Tela

![Captura de Tela 1](img/ANAKE%20GAME%20CAPA.jpeg)
![Captura de Tela 1](img/SNAKE%20GAME.jpg)

