The Maze
The Maze is a 3D maze game that employs ray casting to transform a 2D map into a fully navigable 3D world. This immersive game challenges players to navigate through intricate mazes, providing an engaging and visually dynamic experience.

The Maze was written in C using the SDL2 library. Development was carried out on Ubuntu 24.04 with GCC (Ubuntu 11.3.0-1ubuntu1~22.04) version 11.3.0.

About SDL2
Simple DirectMedia Layer (SDL2) is a cross-platform development library designed to provide low-level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It is widely used in video playback software, emulators, and popular games, including Valve's award-winning catalog and many Humble Bundle games. SDL2 simplifies game development and ensures broad compatibility across different platforms.

Installation

$ git clone https://github.com/Pierre254/alx_maze_project.git

$ ./maze

Use the up and down arrow keys to move forward and backward (keys W and S serve the same function).
Use the right and left arrow keys to turn the camera around (keys D and A serve the same function).

Compilation
$ gcc -Wall -Werror -Wextra -pedantic ./src/*.c -lm -o maze `sdl2-config --cflags` `sdl2-config --libs`
By following these instructions, you can compile and run The Maze on your system, exploring the intricate 3D worlds generated by the game. Enjoy navigating through the mazes and challenging yourself to find the quickest paths to success!
