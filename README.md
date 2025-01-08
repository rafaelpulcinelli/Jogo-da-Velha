# Jogo da Velha Flutter

## Atividade 4 - Disciplina de Desenvolvimento Web
Este projeto consiste em um jogo da velha interativo desenvolvido em Flutter como parte de um exercício da disciplina de desenvolvimento web.

## Acesse a página e o código 
- Link página web: [https://rafaelpulcinelli.github.io/Jogo-da-Velha](https://rafaelpulcinelli.github.io/Jogo-da-Velha/)
- Para acessar o código do projeto, abra a pasta "lib".
  
## 📋 Descrição
O aplicativo implementa um jogo da velha com duas opções de modo de jogo: contra outro humano ou contra o computador. A interface é responsiva e simples, permitindo uma experiência intuitiva e agradável. O código conta com lógica de verificação de vitória e alternância de jogador, além de funcionalidades para reiniciar o jogo e exibir resultados.

## 🚀 Funcionalidades
- **Dois modos de jogo**:
  - Contra outro humano.
  - Contra o computador, com lógica de jogadas inteligentes.
- **Reinício do jogo**: Botão para reiniciar a partida a qualquer momento.
- **Exibição de resultados**: Diálogo informando se houve vitória, derrota ou empate.
- **Modo Computador**:
  - Implementação de lógica para jogadas estratégicas, priorizando vencer, bloquear o adversário ou jogar no centro.
- **Interface aprimorada**:
  - Botão de alternância de modo reformulado para um menu suspenso elegante.
  - Grade organizada do tabuleiro com ícones claros e estilizados (X e O).
  
## 🛠️ Estrutura
O código utiliza:
- **Gerenciamento de estado** com `setState` para alternar entre os jogadores e atualizar a interface.
- **Widgets principais**:
  - `GridView` para a construção do tabuleiro.
  - `PopupMenuButton` para alternar entre os modos de jogo.
  - `AlertDialog` para exibir os resultados das partidas.
- **Estilização**:
  - Botões estilizados com `BoxDecoration` e cores personalizadas.

## 📚 Aprendizado
Este projeto oferece uma ótima prática para:
- Implementação de lógica em jogos com Flutter.
- Utilização de widgets interativos como `PopupMenuButton` e `GridView`.
- Gerenciamento de estado simples com `setState`.
- Criação de interfaces visuais agradáveis e funcionais.

## Acesse o código
Para acessar o código completo do projeto, verifique a pasta `lib` do projeto.
