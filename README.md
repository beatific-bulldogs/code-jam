<img src="images/logo.png" alt="Bulldog Logo" width="200"></img>

# PyDis Code Jam Summer 21: Beatific Bulldogs

This is the Beatific Bulldogs' submission to the Python Discord Code Jam of Summer 2021.

A snake game playable in the terminal.

Includes offline mode and online mode (you can host your own game). The game is controlled using arrows.


## Game
- ### Controls
   To navigate the menus use the arrow keys and to select press `ENTER`. For text inputs you need to type because copy/paste doesnt work.
   To move the snake use the arrow keys.
 - ### Online mode
   To play online you can either join a server or you can host one yourself.
   I it is recommended that you have your terminal on full size so the graphics wont
   be messed up.
- ### Connect to server
   To join a server select the `Connect to server` option and type the server address and port.
   These details will be saved so you can quicly erconnect to the same server. To connect to another server 
   just select `Reset Server Details` and `Connect to server` and enter your new server of choice.
- ### Server hosting
   To start a server select `Host A Server` and type in the game options.
   Each server can theoretically host infinite games consisting of as many players as you specified before.
   When a game fills the server will add all new players to a new one. To quit the server you can simply press `Q`
   and wait for the process to terminate.
- ### Nicknames
   To change your nickname select `Change nickname`. Nicknames are used in online mode
   to display your score on the scoreboard. Your nickname is saved so you dont need to re-enter it
   every time you restart the game.


## Installation

 1. [Install Python](https://python.org/downloads)

    You will need Python 3.9+ (3.x where x >= 9).

 2. [Install Poetry](https://python-poetry.org/docs/master/#installation)

    Installation instructions are available at the above link.

 3. Enter the Poetry shell

    ```shell
    $ poetry shell
    ```

 4. Install development dependencies

    ```shell
    $ poetry install
    ```

## Usage

 - Run the client

   ```shell
   $ poe main
   ```

## Development
 - Install pre-commit hooks

    ```shell
    $ pre-commit install
    ```
    
 - Automatically order imports

   ```shell
   $ poe fix
   ```

 - Lint the code

   ```shell
   $ poe lint
   ```
