# Jogo da Velha em Python
Este é um jogo da velha simples desenvolvido em Python, onde você pode jogar contra o computador. O jogo foi implementado usando a linguagem Python e possui uma interface de linha de comando.

## Funcionalidades:
Escolha entre X e O para jogar.
Jogabilidade contra o computador.
Placar mantido para acompanhar vitórias e empates.

## Como Jogar:
Certifique-se de ter Python instalado em seu sistema.
Execute o script jogo_da_velha.py.
Escolha entre X e O para jogar.
Faça suas jogadas digitando o número correspondente à posição no tabuleiro.
O jogo irá alternar entre suas jogadas e as do computador.
O jogo termina quando alguém vence ou ocorre um empate.
Pressione Enter para continuar jogando ou digite "sair" para encerrar o jogo.

## Explicação do Código:
O jogo foi implementado em duas classes principais:
Jogo_da_velha: Controla o fluxo do jogo, incluindo a inicialização, a entrada do jogador e a exibição do placar.
Partida: Gerencia uma única partida do jogo da velha, incluindo a lógica de jogo, verificação de vitória e movimentos do jogador e do computador.

### Detalhes da Implementação:
A classe Jogo_da_velha gerencia o jogo como um todo, enquanto a classe Partida cuida da lógica individual de cada partida.
O tabuleiro do jogo é representado por uma lista de 9 elementos, onde cada elemento corresponde a uma posição no tabuleiro.
A lógica do jogo inclui a verificação de vitória, empates e movimentos do jogador e do computador.

## Executando o Jogo:
No terminal, navegue até o diretório onde o arquivo `jogo_da_velha.py` está localizado e execute o seguinte comando:
python jogo_da_velha.py
