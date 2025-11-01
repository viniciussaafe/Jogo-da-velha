🎮 Jogo da Velha (Tic-Tac-Toe)

Um jogo simples e clássico da velha implementado com HTML, CSS e JavaScript puro.

💡 Sobre o Projeto

Este é um projeto básico para praticar e demonstrar o uso de HTML, CSS para a estrutura e estilo, e JavaScript para a lógica do jogo (gerenciar turnos, verificar vitória e empates).

✨ Funcionalidades

    Alternância automática de jogadores (X e O).

    Verificação imediata de condições de vitória (linhas, colunas e diagonais).

    Verificação de empate.

    Reinício automático do jogo após vitória ou empate.

🛠️ Tecnologias Utilizadas

    HTML5: Estrutura do jogo.

    CSS3: Estilização e layout (usando Grid para o tabuleiro).

    JavaScript (ES6+): Lógica do jogo.

🚀 Como Jogar

O jogo é puramente front-end e não requer instalação de pacotes ou servidores complexos.

    Clone o repositório (se estiver em um, ou apenas salve os arquivos).

    Abra o arquivo index.html no seu navegador de preferência (clique duas vezes ou arraste para a janela do navegador).

    O jogo começará imediatamente. O Jogador X sempre inicia.

    Clique em qualquer quadrado vazio para fazer sua jogada.

    O jogador que conseguir colocar três de suas marcas em uma linha horizontal, vertical ou diagonal vence!

⚙️ Estrutura dos Arquivos

Arquivo	Descrição
index.html	Estrutura principal da página e do tabuleiro.
style.css	Definições de estilo e layout.
script.js	Lógica principal do jogo (funções init, newMove, check).

📝 Observações sobre o Código

    A lógica de vitória utiliza um array positions que mapeia todas as combinações vencedoras possíveis.

    A função newMove controla o turno e chama check após cada jogada.

    O uso de data-i nos botões HTML é crucial para mapear a posição clicada no array selected do JavaScript.
