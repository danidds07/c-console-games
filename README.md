# Jogos de Console em C

Coleção de jogos de terminal escritos em C, feitos para praticar lógica de programação
nas disciplinas de Algoritmos 1 e 2. São dois jogos independentes que rodam direto no
console, sem bibliotecas externas.

## O que dá para jogar

- **Corrida de Cavalos**: uma corrida simulada com movimento aleatório a cada rodada,
  até um cavalo cruzar a linha de chegada.
- **Jogo da Forca**: o clássico jogo de adivinhar palavras, com número limitado de
  tentativas e desenho da forca atualizado no terminal.

Os dois usam só a biblioteca padrão do C (stdio, stdlib, string, time) para entrada e
saída, geração de números aleatórios e manipulação de texto.

## Tecnologias

- C
- Biblioteca padrão (stdio, stdlib, string, time)
- Interação via terminal

Não há dependências externas nem sistema de build; cada jogo compila sozinho com o gcc.

## Como executar

**Corrida de Cavalos**
```bash
gcc horse-race/corridadecavalos.cpp -o horse-race
./horse-race
```

**Jogo da Forca**
```bash
gcc hangman/jogodaforca.cpp -o hangman
./hangman
```

## Estrutura do projeto
```text
c-console-games/
|-- horse-race/
|   `-- corridadecavalos.cpp
|-- hangman/
|   `-- jogodaforca.cpp
`-- README.md
```

## Contexto acadêmico

Os dois jogos foram feitos como exercício para as disciplinas de Algoritmos 1 e 2,
com foco em laços de repetição, estruturas condicionais, manipulação de strings e
geração de eventos aleatórios.

## Autor

Desenvolvido por Daniel Augusto Silva.
