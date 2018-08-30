# CRAPPY VERSION OF FLAPPY BIRD A.K.A CRAPPYBALL-CX

![Gameplay Screenshot](https://github.com/atang152/crappyBall-cx/blob/master/Screenshot/CrappyBall.gif?raw=true)

CrappyBall-cx is a clone to a popular game called FlappyBird and it is a simple 2D game written in cx. cx is a programming language developed by [Skycoin Team](https://www.skycoin.net/ "Skycoin"). Please note that I am not a developer for the Skycoin team but I do hold Skycoin through my own purchases. The game was developed as my interest to learn the CX language as well as to promote social awareness to Skycoin and their projects. Please note that most codes are based on examples developed and written by [amherag](https://github.com/amherag).

# INSTALL
CrappyBall-cx requires [CX version 0.5.8](https://github.com/skycoin/cx) to run. In order to play it currently, you would need to install the necessary dependencies from https://github.com/skycoin/cx which includes Go, OpenGL and GLFW. Instructions below are from https://github.com/skycoin/cx for Debian-based Linux system. If you have CX installed, you could just skip these process and go straight to cloning the directory and running the game.

### Install GO
1. Install Go (Version greater than 1.8 and 1.10)
2. Congifure $GOPATH environment variable

### Installing OpenGL/GLFW dependencies on Debian-based Linux system
```
sudo apt-get install libxi-dev
sudo apt-get install libgl1-mesa-dev
sudo apt-get install libxrandr-dev
sudo apt-get install libxcursor-dev
sudo apt-get install libxinerama-dev
sudo apt-get install libglfw3-dev
```
### Installing CX
As per https://github.com/skycoin/cx, you need to have the latest version of `curl` and `git` installed. The below script checks if you have all the necessary Golang packages and tries to install them for you. It would then install CX for you.
```
sh <(curl -s https://raw.githubusercontent.com/skycoin/cx/master/cx.sh)
```

Once installation is completed, you should test your installation by running `cx $GOPATH/src/github.com/skycoin/cx/tests`.

### Cloning the CrappyBall-cx repo
After all dependencies are installed and [CX](https://github.com/skycoin/cx) runs correctly. Clone the following depository by running:

```git clone https://github.com/atang152/crappyBall-cx.git```

Navigate to cloned directory:

```cd crappyBall-cx/```

# Running the game
Type in the following command when you are in the crappyBall-cx folder.

```cx main.cx```

or

```cx *.cx```

# TO DO...
Alot of things. The current codebase is utter crap and needs to be completely refractored. I am still in the process of learning the cx language... e.g

1. Figure how to load sprites
2. Refractor game into a more Entity-Component-System architecture
3. Use VAO/VBO for rendering instead of OpenGL primitives
4. Figure out how to build game into binary

# Hi Sudo. This is Anto. Just doing a commit here to let you it's me. Thanks!


