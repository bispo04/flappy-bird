# 🐦 Flappy Bird com Pygame

Este é um projeto feito em Python que recria o clássico jogo **Flappy Bird**, usando a biblioteca **Pygame**. O objetivo do jogo é simples: conduzir o pássaro pelos canos sem colidir e acumular pontos.

---

## 🎮 Como Jogar

- Pressione a **barra de espaço (ESPAÇO)** para fazer o pássaro voar.
- Evite bater nos canos ou cair no chão.
- Quando perder, pressione:
  - **ESPAÇO** para reiniciar o jogo.
  - **ESC** para sair do jogo.

---

## 📁 Estrutura do Projeto

flappy-bird/
│
├── ima/ # Imagens do jogo
│ ├── bird1.png
│ ├── bird2.png
│ ├── bird3.png
│ ├── pipe.png
│ ├── base.png
│ └── bg.png
│
├── flappy_bird.py # Código principal
└── README.md # Este arquivo

yaml
Copiar
Editar

---

## ✨ Funcionalidades

- Animação do pássaro com diferentes sprites
- Colisões precisas usando máscaras (`pygame.mask`)
- Geração infinita de canos com alturas aleatórias
- Pontuação com interface na tela
- Tela de fim de jogo com opção de reinício

---

## ⚙️ Requisitos

- Python 3.x
- Pygame

Instale o Pygame com:

```bash
pip install pygame
▶️ Como Executar
Execute o jogo com o comando:

bash
Copiar
Editar
python flappy_bird.py
✅ Dicas
Se quiser ajustar a dificuldade, edite os seguintes valores no código:

Velocidade do pássaro: Passaro.velocidade

Velocidade dos canos: Cano.VELOCIDADE

Espaçamento entre canos: Cano.DISTANCIA

📦 .gitignore recomendado
Crie um arquivo chamado .gitignore na raiz do projeto com o conteúdo abaixo para evitar subir arquivos desnecessários ao GitHub:

markdown
Copiar
Editar
__pycache__/
*.pyc
.idea/
*.log
🧑‍💻 Autor
Desenvolvido por Vitor Bispo Borges
Projeto educacional baseado no clássico Flappy Bird.

