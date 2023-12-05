# Termo
Descrição
Este é um jogo de adivinhação de palavras de 5 letras inspirado no 'Termo', onde os jogadores devem tentar descobrir uma palavra escolhida escolhida pelo sistema. O jogo oferece diferentes modos de dificuldade: Padrão, Dueto e Quarteto. O desafio aumenta à medida que o número de palavras a serem adivinhadas simultaneamente aumenta, e os jogadores têm um limite de tentativa para acertar.

Arquitetura do Sistema
O sistema é dividido em módulos para diferentes funcionalidades:

Módulo Principal: Responsável por gerenciar o fluxo principal do jogo, exibindo opções de jogo, redefinindo palavras salvas e encerrando o jogo.
Motivo do Módulo: Contém a lógica do jogo com funções relacionadas à manipulação e leitura de palavras.
Module Clear: Oferece funcionalidades para limpar a tela e arquivos de palavras utilizadas.
Funcionalidades
Carregamento de Palavras: O jogo carrega palavras de um arquivo de texto, tanto para palavras a serem adivinhadas quanto para as palavras já utilizadas.
Seleção de Modo de Jogo: Oferece opções de modos de jogo, com diferentes níveis de dificuldade e número de palavras a serem adivinhadas simultaneamente.
Adivinhação de Palavras: O jogador insere palavras de 5 letras para tentar adivinhar as palavras sorteadas.
Limpeza de Palavras Utilizadas: Permite ao jogador limpar as palavras já utilizadas para reiniciar o jogo.
Como jogar
Execute o código em um ambiente compatível com Python.
Siga as instruções exibidas no console:
Escolha entre as opções oferecidas: Selecionar Modo de Jogo, Redefinir Lista ou Sair.
Selecione o modo de jogo desejado: Padrão, Duo ou Quarteto.
Insira palavras de 5 letras para tentar adivinhar as palavras sorteadas.
Ao finalizar ou esgotar as tentativas, decida se deseja jogar novamente.
Regras do Jogo
Padrão: Adivinhe uma palavra em 5 esforços.
Duo: Adivinhe duas palavras simultaneamente em 6 tentativas.
Quarteto: Adivinhe quatro palavras simultaneamente em 8 tentativas.
Pedro Henrique e William
