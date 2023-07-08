# The Maze 

The Maze is a video game where players navigate through a maze-like environment to reach a goal while avoiding obstacles and challenges along the way.

# <a href="https://xion-pixl.github.io/">Visit Landing Page</a>

This Project was created was with C using SDL2 library. and built on Ubuntu 14.04 LTS - gcc (Ubuntu 4.8.4-2ubuntu1~14.04) 4.8.4





> # Instalation 
1. Clone From github repo 
    ```ss
    $ git clone https://github.com/moanbekele/Maze-project
    ```
1. Installiation(Linux)
*   `sudo apt install build-essential` Install GCC compiler
*   `sudo apt install libsdl2-dev` Install SDL-2
  
* <a href="https://www.youtube.com/watch?v=XfZ6WrV5Z7Y">Installiation for other Operating Systems</a>

>   # Exexution 
* Execute `./game` or type `make run` 
* Press up and down arrow keys to move forward and backward 
* Press right and left arrow keys to turn the camera arround

>   # Compilation
```sh
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o game `sdl2-config --cflags` `sdl2-config --libs`;
```



