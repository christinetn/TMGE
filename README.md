# TMGE

**How to Run**

CD into the jar folder and run `java -jar TMGELoader`
You may need to add the option `--enable-preview`


## Description
Created a tile maching game engine that accomodates the games SameGame and Bejeweled. 


**Requirements**
- The TMGE should accommodate any tile-matching game that involves a grid layout and game elements on this layout, including games such as Tetris, Klax, Bejeweled, Bust-a-Move, Puzzle Bobble, Candy Crush, Dr. Mario, Puzzle Fighter, etc.
- The TMGE should make it as easy as possible to create implementations of new games.
- The TMGE should provide a defined interface that all games built on top of the environment must follow.
- The TMGE should support two players running on the same local machine.
  -	If your game supports networked multiplayer, you can get up to 5% extra credit for this project.
- The TMGE should support personal player profiles (the specifics of which are up to you). Login can be very simple and does not have to be secure.
- The TMGE need only support 2-player games (but you can support more players if you want to).
- The TMGE should work by providing a player with a list of games they can play and allow them to choose which one to start.
- The TMGE  should be written in Java with modules specified and implemented using the Java Platform Module System.
  - Up to 5% extra credit for this assignment if you use Java modules that consume or provide services, by leveraging the uses and provides directives, in a sensible and effective manner
- The TMGE should only expose parts of itself necessary to build a game, hiding the internals of the TMGE that need not be used or extended by a game directly.
- The TMGE  only needs to support running one game at a time.
