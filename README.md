## Game Engine

A 2D game engine for a simple physics platformer game. 


## How To Install & Run (Linux)

1. Install the C++ compiler g++ using the following command:
```bash
sudo apt-get install g++
```

2. To check which version is installed run the following command:
```bash
g++ --version
```

3. Install the SDL2 library using the following command:
```bash
sudo apt install libsdl2-image-dev
```

4. Clone the remote repository to your local machine using the following command:
```bash
git clone https://github.com/frederic-hallein/game-engine
```
5. To compile the project, go inside the `double_pendulum/` directory and run the following command: 
```bash
make all
``` 
This should create a `main` executable file in the same directory. 

6. Run the executable by using the following command: 
```bash
./main
```

## Controls

Character control is done using the `wasd` keys. \
`a`     : move left \
`d`     : move right \
`SPACE` : jump and double jump 


