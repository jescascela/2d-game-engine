# Visão Geral
Repositório destinado ao estudo da biblioteca SDL. O jogo em desenvolvimento é baseado no tutorial do canal [Let's Make Games](https://www.youtube.com/playlist?list=PLhfAbcv9cehhkG7ZQK0nfIGJC_C-wSLrx)

# Executando o projeto no Linux
1. Instale a biblioteca SDL2 através do terminal utilizando comando ``sudo apt-get install libsdl2-dev``
2. Instale a biblioteca de extensão do SDL utilizando ``sudo apt-get install libsdl2-image-dev``
3. Clone o repositório
4. Para compilar o projeto, utilize o GNU g++ executando o comando ``g++ main.cpp Game.cpp TextureManager.cpp GameObject.cpp Map.cpp -o main `sdl2-config --cflags --libs` -lSDL2_image``
