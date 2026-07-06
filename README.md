# Plataforma Aventura

Um jogo de plataforma 2D desenvolvido em **Python** utilizando a biblioteca **PGZero**.

## 🎮 Sobre o jogo

Controle o personagem por uma fase repleta de desafios: colete todas as moedas para vencer, enquanto desvia de inimigos que podem colocar um fim rápido à sua jornada.

## 🕹️ Como jogar

- **Setas esquerda/direita**: mover o personagem
- **Espaço**: pular
- **Objetivo**: coletar todas as moedas do cenário
- **Cuidado**: evite tocar nos inimigos (serras e ratos) — o contato encerra o jogo imediatamente

## ✨ Funcionalidades

- Animações para os inimigos (serras e ratos)
- Detecção de colisão com moedas, plataformas e inimigos
- Efeitos sonoros de pulo, coleta de moedas, derrota e vitória
- Interface de início com botões **Começar** e **Sair**
- Controle de som (mudo/desmudo)
- Verificação de vitória e derrota, com telas especiais para cada resultado

## 🛠️ Tecnologias utilizadas

- [Python](https://www.python.org/)
- [PGZero](https://pygame-zero.readthedocs.io/)

## ▶️ Como executar

1. Certifique-se de ter o Python instalado.
2. Instale o PGZero:
   ```bash
   pip install pgzero
   ```
3. Execute o jogo com o comando:
   ```bash
   pgzrun nome_do_arquivo.py
   ```

## 🏆 Condições de fim de jogo

- **Vitória**: todas as moedas foram coletadas
- **Derrota**: o personagem tocou em um inimigo (serra ou rato)
