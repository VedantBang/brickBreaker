# brickBreaker

Here is a small game made using the JavaScript library known as [PixiJS](https://www.pixijs.com/).

PixiJS runs only on a webserver, so following are the steps to set up a simple web server and get the game running:
1. Download and install [NodeJS](https://nodejs.org/en/) on your machine. If you already have it installed, you can skip this step.
2. [Download](https://github.com/VedantBang/brickBreaker/archive/master.zip) the contents of this repository and save them in a suitable destination on your computer.
3. Open up the terminal/command line on your machine and navigate to the directory where the game is stored. (If you are new to the terminal, I would recommend [this](https://medium.com/@zibon/basic-linux-command-lines-to-get-started-developing-in-ubuntu-linux-b54def1c2190) tutorial.)
4. We shall be using a NodeJS package called "http-server" to set up our own local webserver. Download the package by using the command ``npm install -g http-server`` on your terminal window.
5. We are almost there! Now we will be running the server. Type in ``http-server`` in the terminal. Make sure that you in are the directory which contains the game files.
6. If everything goes fine, you should get an output simlilar to this.
 
```
Starting up http-server, serving ./
Available on:
  http://127.0.0.1:8080
  http://10.20.4.165:8080
Hit CTRL-C to stop the server
```
7. Now open your browser, and type in the address that is displayed on your terminal screen. A page will open up which will look just like a file explorer. Navigate to a file called as game.html and open it.
8. And that's all that is required! Arrow keys to play!
