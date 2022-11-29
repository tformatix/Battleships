# Battleships
Android App of the game Battleships (German: Schiffe versenken) <br/>
Project for Mobile Computing study in FH Hagenberg

Google Play: https://play.google.com/store/apps/details?id=at.fhooe.mc.android.battleships

## Screenshots
<div style="width: 1000px; height: 600px;">
    <img width="25%" src="https://user-images.githubusercontent.com/45870302/204643739-2897d181-4d66-464c-99a8-1dae27640cda.png"/>
    <img width="25%" src="https://user-images.githubusercontent.com/45870302/204643770-4b796bfc-9b34-47ae-bec9-986d820d4e47.png"/>
    <img width="25%" src="https://user-images.githubusercontent.com/45870302/204643785-742e0803-59a8-4ba3-9d11-8bd1a56ef040.png"/>
</div>

## Game
* strategy guessing game
* played on grids
  * ships with different sizes are marked on the grid
* location of the opponent’s ships must be guessed
  * player “shoots” on ships
  * a ship is sunken, when the player located the whole ship
* if every of the opponent’s ships are sunken
  * player won
## Rules
* one ship must be built in one row or one column
  * not diagonal
* ships must not collide with each other
  * one cell at minimum has to be free between every ship
## Features
* offline multiplayer
  * playing on only one phone
* selecting number of ships used in the game
  * available ship sizes: 5, 4, 3 and 2
  * 0 to 5 ships per size
* selecting board size (number of rows and columns)
  * 5 to 20 rows/columns
  * for example: 10x10 field
* checking wrong user input
  * colliding ships, unavailable ship used, …
## Project Structure
### Overview
![grafik](https://user-images.githubusercontent.com/45870302/124254729-a434d500-db29-11eb-9616-6e4b0ae0962e.png)
### Background Logic
![grafik](https://user-images.githubusercontent.com/45870302/124254255-2a045080-db29-11eb-93ed-db54a154c9b6.png)
