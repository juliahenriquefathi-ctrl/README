# README
Leonardo Henrique Faria Dias

Alexandre Aguilar Pistolato Lopes

Nome do Projeto
Jogo da Velha com LEDs e Arduino

Resumo
O projeto é um jogo da velha eletrônico onde LEDs representam as jogadas e o Arduino controla todo o funcionamento. O jogador X é representado pelo LED amarelo e o jogador O pelo LED azul. Quando um jogador forma três em sequência, o Arduino apaga todos os LEDs e reinicia o jogo

Descrição
O tabuleiro é formado por nove posições, conectadas individualmente ao Arduino. Cada posição possui dois LEDs, um amarelo e um azul, e um botão responsável por registrar a jogada naquela casa. O jogador X sempre inicia a partida. Quando um botão é pressionado, o Arduino verifica se a casa está livre, acende o LED correspondente ao jogador da vez e registra a jogada em memória. Após cada ação, o sistema analisa automaticamente todas as combinações possíveis para identificar uma vitória ou um empate. Em caso de vitória, todos os LEDs são apagados e o tabuleiro é reiniciado para uma nova rodada. Esse funcionamento demonstra lógica de programação, controle de estados e interação entre hardware e software.

Desafio da Semana do Industrial
O desafio proposto durante a Semana do Industrial era criar um projeto eletrônico funcional utilizando Arduino como plataforma principal. O objetivo era aplicar, na prática, conceitos de eletrônica básica, lógica de programação, montagem de circuitos, organização de tarefas e trabalho em equipe. O jogo da velha foi escolhido porque combina tomada de decisão, verificação lógica e interação do usuário, além de permitir a montagem de um circuito claro e visível para demonstração durante o evento.

Hardware e Software Utilizados
Arduino Uno R3
Protoboard para montagem do circuito
LEDs amarelos (para o jogador X)
LEDs azuis (para o jogador O)
Resistores para proteção dos LEDs
Botões para selecionar cada casa do tabuleiro
Jumpers para realizar as conexões
Arduino IDE para programação em C++
Tinkercad para testes e simulação do circuito (opcional)
