# 3D-Game-of-Life
3D coding project to demonstrate the Game of Life concept with a twist in honor of John Conway
The purpose of the Game of Life isn't to actually simulate the process of life and evolution, but it's a way to demonstrate how more complex shapes and states can form
from simple rules of the world. This is somewhat similar to how life works. Normally the Game of Life is one a 2D board and has the following rules:
Any live cell with fewer than two live neighbours dies.
Any live cell with two or three live neighbours lives.
Any live cell with more than three live neighbours dies.
Any dead cell with exactly three live neighbours becomes a live cell.

This 3D game takes place in a 3D cubic space and has the following rules:
Any live cell with fewer than two live neighbours dies.
Any live cell with two or three live neighbours lives.
Any live cell with more than three live neighbours dies.
Any dead cell with exactly five live neighbours becomes a live cell.

Those are in the hard generation setting, the easy 3D game uses the same rules as the 2D version. This is coded with javascript using Three.js. Download the three.js-master folder from https://threejs.org/ and put the three.js-master folder in the same folder as the Game of Life.html file in order for the project to run.

