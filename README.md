# Agario
An analogue of the game agario.

# Playing the Game
this is a game in which bacterial cells move around, absorb food pellets, and also eat each other.
the game ends when you are absorbed by another player, in our case by bot.
The essence of the game is to absorb other players and become the biggest bacteria.
![Screenshot from 2022-04-06 01-55-27](https://user-images.githubusercontent.com/79391708/161839031-f178636b-9284-4f10-8600-bdd129043cb6.png)

# How to run game code?
1. Download this code, or use git commands 'git clone'
2. Аctivate virtual environment '. env/bin/ctivte'
3. Run game.py(to run server) and main.py (to join game)

# Game Mechanics
- food pellets appear randomly across the entire area of this screen
- bots also appear randomly and each has its own trajectory
- large bacteria are able to absorb small ones, thereby increasing in size
- the bigger the bot, the lower its speed
