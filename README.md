# RL Gym Taxi Teste 🚖🧠

Projeto simples utilizando **Aprendizado por Reforço (Reinforcement Learning)** no ambiente `Taxi-v3` da biblioteca **OpenAI Gym**, com renderização em modo texto (`ansi`). Desenvolvido em um Jupyter Notebook com o objetivo de demonstrar, de forma didática, como funciona o algoritmo Q-Learning aplicado a um agente que aprende a pegar e deixar passageiros em um mapa simples.

## 🧠 Sobre o projeto

Este projeto treina um agente a navegar por um mapa 5x5 simulando um táxi que deve buscar um passageiro em um local e deixá-lo em outro. O agente aprende com tentativa e erro, recebendo recompensas positivas ou penalidades a cada ação, até dominar a tarefa.

- Ambiente: `Taxi-v3` (`gym.make('Taxi-v3', render_mode='ansi')`)
- Algoritmo: **Q-Learning**
- Saída: renderizada no terminal com atualização de frames (simulando uma animação em texto)
- Plataforma: **Jupyter Notebook**

## 📚 Conceitos utilizados

- **Espaço de Estados e Ações** do Gym
- **Tabela Q (Q-Table)**: matriz 500x6 com os valores Q de cada par estado-ação
- **Exploração vs Exploração (epsilon-greedy)**
- **Aprendizado por reforço com Q-Learning**
- **Visualização ANSI no terminal (modo texto)**

## ⚙️ Dependências

- Python 3.x
- `gym`
- `numpy`
- `IPython`

Instale as dependências com:

```bash
pip install gym[all] numpy ipython
