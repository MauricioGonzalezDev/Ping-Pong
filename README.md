🎮 Jogo Ping-Pong — HTML, CSS e JavaScript

Este projeto consiste na criação de um jogo de Ping-Pong utilizando HTML, CSS e JavaScript.
O jogo foi construído dentro do elemento canvas, onde os objetos (bolas, raquetes, linha central e campo) são desenhados e atualizados continuamente usando animações em tempo real.

O jogador controla a raquete esquerda com o mouse, enquanto a raquete direita utiliza uma lógica automática que tenta acompanhar a bola.
O placar atualiza automaticamente e a dificuldade aumenta conforme o jogo avança.

🔗 GitHub Pages --> https://mauriciogonzalezdev.github.io/Ping-Pong/

🎯 O que eu aprendi
1. Manipulação do Canvas

Aprendi a utilizar o contexto 2D do canvas para desenhar:

Retângulos

Bolas

Atualizar elementos a cada frame
Métodos utilizados: fillRect(), arc(), beginPath(), fill()

2. Lógica de movimento

Compreendi como movimentar objetos na tela usando:

Coordenadas x e y

Direção

Velocidade

Atualizações quadro a quadro (60 FPS)

3. Detecção de colisão

Implementei verificações de colisão entre a bola e:

Paredes

Teto e chão

Raquetes
Foi essencial para manter a bola em jogo e ajustar sua direção.

4. Interação com o usuário

Implementei o movimento da raquete esquerda usando:
canvasEl.addEventListener("mousemove")
Isso permite ao jogador mover sua raquete suavemente.

5. Inteligência Artificial simples

A raquete direita segue a bola usando uma lógica automática básica, criando a sensação de jogar contra o computador.

6. Animação com requestAnimationFrame

Aprendi a usar requestAnimationFrame() para atualizar o jogo na velocidade ideal, criando animações fluidas.

7. Organização de código

Estruturei o código criando objetos como:

field

leftPaddle

rightPaddle

ball

score

Cada um possui funções internas (draw, move, etc.), facilitando a leitura e manutenção.

📁 Estrutura de pastas
/
├── index.html   # Arquivo principal do jogo
└── script.js    # Lógica do jogo e animações

🚀 Futuras melhorias

Tela inicial com menu

Opções de dificuldade

Modo multiplayer local

Melhorias na IA

Efeitos sonoros e trilha

Novos modos de jogo

✅ Conclusão

Desenvolver este jogo foi excelente para praticar lógica, estrutura de código e renderização gráfica com canvas. Além de reforçar muitos fundamentos do JavaScript.
A partir daqui posso evoluir com sons, modos de dificuldade, IA avançada ou menu inicial.
