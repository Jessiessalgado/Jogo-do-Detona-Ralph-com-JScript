# 🎮 Jogo Detona Ralph - JScript

Um jogo interativo onde o objetivo é clicar no maior número de alvos no tempo disponível.

---

## Índice

- [Visão Geral](#visão-geral)
- [Demonstração](#demonstração)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Rodar o Projeto](#como-rodar-o-projeto)
- [Estrutura do Código](#estrutura-do-código)
- [Contribuições](#contribuições)
- [Licença](#licença)

---

## Visão Geral

Este projeto é um simples jogo de clique, onde o jogador deve clicar em alvos que aparecem aleatoriamente na tela. Com o tempo limitado, o jogador precisa ser rápido para alcançar a maior pontuação possível!

---

## Demonstração

![Demonstração do Jogo](./src/images/jogo.png)



---

## Funcionalidades

- 🎯 **Alvos Aleatórios**: Cada alvo aparece em uma posição aleatória dentro da área de jogo.
- ⏱️ **Contagem Regressiva**: O tempo limite de 60 segundos para cada partida.
- 🔊 **Efeitos Sonoros**: Feedback sonoro ao acertar o alvo.
- 📈 **Pontuação em Tempo Real**: Pontuação atualizada a cada acerto.

---

## Tecnologias Utilizadas

- **HTML5**: Estrutura da página.
- **CSS3**: Estilização e layout do jogo.
- **JavaScript**: Lógica do jogo, controle de tempo e pontuação.

---

## Como Rodar o Projeto

### Pré-requisitos

Para rodar o projeto, você precisa apenas de um navegador web moderno.

### Passo a Passo

1. Clone o repositório:
   ```bash
   git clone https://github.com/Jessiessalgado/Jogo-do-Detona-Ralph-com-JScript

2. Navegue até o diretório do projeto:
   ```bash
   cd Jogo-do-Detona-Ralph-com-JScript

3. Abra o arquivo `index.html` no navegador.

### Estrutura do Código
Aqui está uma visão geral dos principais arquivos e pastas do projeto:

📦 Nome_Do_Projeto
├── 📁 src
│   ├── 📁 audios
│   │   └── hit.m4a           # Som de feedback ao acertar o alvo
│   └── 📄 main.js            # Código principal do jogo
├── 📄 index.html             # Estrutura HTML do jogo
├── 📄 style.css              # Estilos do jogo
└── 📄 README.md              # Documentação do projeto

### Explicação de Algumas Funções

- **`randomSquare()`**: Seleciona um quadrado aleatório para o alvo.
- **`countDown()`**: Controla o tempo restante e exibe "Game Over" quando o tempo acaba.
- **`addListenerHitBox()`**: Adiciona eventos de clique nos alvos e atualiza a pontuação.

### Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue para relatar problemas ou sugerir melhorias, ou para fazer um fork do projeto e enviar um pull request.

###Contato
Criado por Jessica. Entre em contato por [LinkedIn](https://www.linkedin.com/in/jessicasilvasalgado/) ou por email: jessica.silvasalgado@icloud.com.

### Notas Finais
Espero que você se divirta jogando e, se tiver alguma sugestão ou ideia para melhorias, sinta-se à vontade para compartilhar!