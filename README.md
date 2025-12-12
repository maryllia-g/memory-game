🧠 Memory Game — Projeto de Jogo da Memória

Este projeto consiste em um Jogo da Memória desenvolvido em HTML, CSS e JavaScript, com suporte a múltiplos temas selecionáveis pelo usuário.
O objetivo é combinar cartas iguais antes que o tempo acabe.

🚀 Funcionalidades

Tela de Login
O jogador informa seu nome antes de iniciar.

Tela Home
Exibe três universos temáticos do jogo:

Rick and Morty

A Casa Coruja

Hora de Aventura

Ao clicar em um deles, o jogador é levado para o jogo com as cartas daquele tema.

Tela de Jogo

Mostra o nome do jogador.

Timer para registrar o tempo de conclusão.

Grade de cartas embaralhadas.

Cada carta tem:

Uma imagem frontal (personagem).

Um verso comum para todas as cartas.

Sistema de verificação de pares corretos.

Quando todas as cartas são combinadas:

Exibe mensagem de vitória.

Redireciona automaticamente para a Home.

🗂 Estrutura de Pastas
memory-game/
│
├─ css/
│   ├─ reset.css
│   ├─ home.css
│   ├─ game.css
│   ├─ login.css
│
├─ image/
│   ├─ rick/
│   │   ├─ beth.png
│   │   ├─ jerry.png
│   │   └─ ...
│   ├─ coruja/
│   │   ├─ eda.jpg
│   │   ├─ luz.jpeg
│   │   └─ ...
│   ├─ aventura/
│       ├─ finn.png
│       ├─ jake.png
│       └─ ...
│
├─ js/
│   ├─ home.js
│   ├─ login.js
│   ├─ game.js
│
├─ pages/
│   ├─ home.html
│   └─ game.html
├─ index.html
└─ README.md


Importante: As imagens de cada tema devem ser colocadas em suas pastas correspondentes e o código deve usar a extensão real dos arquivos .png, .jpg, .jpeg, .webp, etc.

⚙️ Como Funciona o Carregamento das Cartas

O tema selecionado na Home é salvo no localStorage.

O game.js lê esse tema e carrega as imagens da pasta correspondente.

Todas as cartas usam:

back padrão: image/cerebro.png

front: imagens individuais do tema selecionado

▶️ Como Jogar

Acesse login.html.

Digite seu nome.

Escolha um universo.

Combine todos os pares o mais rápido possível.

Quando vencer, você será direcionado de volta para a tela Home.

🧩 Problemas Comuns

Imagem não aparece → extensão errada (.png ≠ .jpg).

Tema não carrega → nome da pasta não corresponde ao usado no JS.

Back das cartas não aparece → caminho incorreto para cerebro.png.

📌 Objetivo da Tarefa

O objetivo desta tarefa foi:

Criar um jogo da memória funcional.

Trabalhar com manipulação de DOM em JavaScript.

Usar localStorage.

Organizar um projeto com múltiplas páginas e múltiplos temas.

Praticar HTML sem frameworks.
