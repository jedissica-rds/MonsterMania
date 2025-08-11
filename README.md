# MonsterMania
![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)  
![Pygame](https://img.shields.io/badge/Pygame-2.x-green?logo=python)  
![Status](https://img.shields.io/badge/status-complete-success)  
![License](https://img.shields.io/badge/license-academic-lightgrey)  


Projeto desenvolvido como parte da disciplina Laboratório de Programação de Computadores I da Universidade Estadual do Amazonas (UEA).
O jogador assume o papel de um monstro que deve sobreviver a ondas cada vez mais perigosas de goblins, coletar power-ups e lutar até ser o último de pé.

---

## Sobre o jogo

- Gênero: Top-down shooter
- Motor: Pygame
- Objetivo: Sobreviver ao máximo de ondas possível, derrotando inimigos e escolhendo power-ups estratégicos.

---

## Mecânicas principais

- Movimento: Use as teclas W, A, S, D para mover o personagem.
- Tiro direcional: Use as setas ↑, ↓, ←, → para atirar em diferentes direções.
- Power-ups: Após cada onda, escolha entre opções como:
- Aumentar velocidade
- Recuperar vida
- Aumentar dano
- Multiplicar disparos
- Ondas de inimigos:
- Goblins comuns: Causam dano ao encostar.
- Goblins atiradores: Disparam sempre que você entra no campo de visão.
- Goblins snipers: Atiram através de paredes.

---

## 🕹️ Gameplay  
![Gameplay](<img width="710" height="748" alt="Captura de Tela 2025-08-11 às 11 22 02" src="https://github.com/user-attachments/assets/d88c4ee7-d9a9-486a-af2d-0d4d9d7a496e" />)  

- **Movimento:** `W` `A` `S` `D`  
- **Disparo direcional:** Setas `↑` `↓` `←` `→`  
- **Power-up:** `Espaço`  

💥 **Tipos de inimigos:**  
- **Goblin Comum:** dano por contato.  
- **Goblin Atirador:** dispara quando você entra na linha de visão.  
- **Goblin Sniper:** atira através das paredes.

---

## Estrutura do Projeto
```
📦 monster-mania
├── assets/                 # Sons, imagens e fontes
├── button.py
├── enemy.py
├── floors.py
├── life.py
├── main.py                 # Arquivo principal do jogo
├── player_behavior.py
├── player_shots.py
├── power_ups.py
├── screen.py
├── shot.py
├── text_display.py
├── wave_controller.py
├── waves.py
└── README.md

```

## Como executar:

- Clone o repositório
  
```
git clone https://github.com/usuario/monster-mania.git
cd monster-mania
```

- Instale as dependências
Certifique-se de ter o Python 3 instalado e instale o Pygame
  
```
pip install pygame
```

- Execute o jogo
```
python main.py
```

## Equipe de Desenvolvimento
```
Jessica Rodrigues de Souza
João Pedro Telles Paes
Isabela Braga Dutra Buleje
```

## Créditos de áudio
```
Sons retirados do Pixabay com atribuições a:
Driken Stan
Ribhav Agrawal
UNIVERSFIELD
floraphonic
```

### Licença
```
Este projeto foi desenvolvido para fins acadêmicos, sem fins comerciais.
```

