# cs56-games-blackjack

This is a current working version of a Blackjack game with a GUI. It can also be found at these links:

* [Archive page](https://foo.cs.ucsb.edu/cs56/issues/0000866/)
* [Mantis page](https://foo.cs.ucsb.edu/56mantis/view.php?id=866)

project history
===============
```
 W14 | andrewberls 5pm | ericpalyan | (jstaahl) Blackjack game
```

## Running the game

simply use the command:
```
ant run
```

![](http://i.imgur.com/rXE5Qe1.png)

## Recent changes
* Improved Javadoc
* Refactored files and directories to appropriately reflect current quarter (Winter 2014)
    * Previous: edu.ucsb.cs56.s13.Blackjack
    * Current: edu.ucsb.cs56.projects.game.blackjack
* Removed JWS references
* Added more JUnit tests
* Removed uneccessary build.xml targets (github handles those for us)
* Added Currency & Betting
* Added How To Play
* Added Double Down
* Cleaned up code and added comments
* Cleaned up and improved the GUI

## Possible improvements

* Online Multiplayer Blackjack - Using a server-client set up and java's built in socket libraries, create a blackjack game that two users can play on separate computers.
* Allow players to change the bet amount at the end of each round
* Allow a player to back out of the game
* Add in game statistics
* Save/load feature

## Other former Blackjack projects

These are past projects which may have similar/missing features. 

* [cs56_W12_492](https://foo.cs.ucsb.edu/cs56/issues/0000492/lab09b/)
* [cs56_W12_443](https://foo.cs.ucsb.edu/cs56/issues/0000443/)
* [cs56_S11_360](https://foo.cs.ucsb.edu/cs56/issues/0000360/)
* [Simple classes for PlayingCard, Deck, BlackJackHand](https://foo.cs.ucsb.edu/cs56/issues/0000215/)



W16 final remarks
-------------------
Most of the code you will be working on will be located in the BlackJackGui.java file. Things will be much easier if you can separate the code inside that file and put them into their own separate files because currently BlackJackGui.java is a very long file with literally every single frame the game uses. There are still some bugs in the game: ex.) When a player tries the "Add Money?" button. All the bugs are related to the GUI and not the game logic.

