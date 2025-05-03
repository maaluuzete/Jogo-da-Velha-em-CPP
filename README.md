# Jogo da Velha em CPP
Feito com base no exercício [Jogo da Velha em C++](https://neps.academy/br/project/22), do [Neps Academy](https://neps.academy). Este é um jogo de dois jogadores, em modo texto, no qual os participantes se alternam para marcar posições em um tabuleiro 3x3 até que um deles vença ou ocorra um empate.

## Demonstração
O jogo inicia exibindo o tabuleiro com as posições numeradas:
```
 1 | 2 | 3
-----------
 4 | 5 | 6
-----------
 7 | 8 | 9
```
O jogador 1 começa e insere a posição desejada:
```
Jogador 1 (X), escolha uma posição: 5
```
O tabuleiro é atualizado automaticamente após cada jogada:
```
 1 | 2 | 3
-----------
 4 | X | 6
-----------
 7 | 8 | 9
```
## Instalação e Pré-requisitos
Para compilar e executar o quiz interativo em C++, é necessário ter o compilador GCC (GNU Compiler Collection) instalado em seu sistema. Abaixo, estão as instruções resumidas para os principais sistemas operacionais:
- **Windows**
  - Baixe o MinGW-w64:
  Acesse a página oficial do MinGW-w64 e baixe o instalador apropriado para o seu sistema: [MinGW-w64](https://www.mingw-w64.org)
  Abra o prompt de comando e digite `g++ --version` para verificar se o compilador GCC está instalado corretamente.
- **Linux**
  - Abra um terminal e execute os seguintes comandos:
```
// Para Debian/Ubuntu, com o apt:
sudo apt-get update
sudo apt-get install g++

// Para Arch Linux:
sudo pacman -S g++
```
## Estrutura do Projeto
Este projeto possui a seguinte estrutura:   

```
    Jogodavelha/  
    │── jogodavelha.cpp
    │── LICENSE 
    │── README.md     
```
* `jogodavelha.cpp` contém o código fonte do jogo da velha.
* Este arquivo é o próprio `README.md`. Ele tem informações sobre o projeto.
* `LICENSE` contém toda a licença do projeto.
## Licença
Este projeto está licenciado sob a licença MIT. Para mais detalhes, consulte [LICENSE](https://github.com/maaluuzete/Jogo-da-Velha-em-CPP?tab=MIT-1-ov-file) incluído neste repositório.
