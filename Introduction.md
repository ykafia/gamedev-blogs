# The art of game development

Hi everyone, I discovered Stride and hope to help people with Stride and GameDev through this blog post. It's a compilation of thoughts to make people start their journey with Stride without issues, can also serve as a tutorial.

We will go through art and video game development and explain how keeping in mind that video game development is an art form will help you understand how a game engine works.

In order to make a video game we first need to know how to make two things

## Video

A best example of videos are movies.

Movies are usually a sequence of pictures with sound, in older movies you could have silent ones, some accompanied by a music band, in newer ones you could experience vibrations, smell etc. The core idea stays a sequence of pictures with sound.

The creation of a movie can be seen as a process :

![image](movie.png)

<!-- 1. Concept :
    This is when the directors with some artists will lay down the story and the visual appearence of the movie. A lot of the physical assets of the movies will be created around that time by artists. These assets can be either buildings, structures, sculptures, paintings etc.

2. Shooting :
    After creating the concepts, the scenes are shot, sometimes in order, sometimes not. 3D effects can also be prepared at that moment depending the complexity of the project. This part of the process is aimed at creating a maximum of usable content for the next step...

3. Compositing :
    Once all the videos are shot, everything is brought together, selected and modified to be the closest to what the director originally envisionned. Special effects can be added, 3D effects and real life images can be merged together, colors can be changed etc. -->

## Game

Games are made with a set of rules and players and each player can make actions to influence the state of the game all while following the rules.

There are a lot of discussions on how to define games, but since we're not trying to get philosophical let's look at four games in particular to help us get an idea on how game are built.

* __Coin toss__ :

    Players call for a side of the coin, toss it and the player that predicted the visible coin side wins.
    Rules makes use of randomness and statistics.

* __The floor is lava__ :
  
    Players can on any surface but the floor, otherwise they lose.
    Rules makes use of the environment

* __Tag game__ :

    A player is tagged and has to physically touch another player to give the tag, the tagged person in the end of the game loses.
    Rules makes use of the social status of players

* __Tic-tac-toe__ :
  
    This one is a bit complicated to explain so you can look it up :D. The main idea is to align symbols before the other player can do it.
    Rules makes use of the status of the board.

Those games are either played in an area, as a sport, with props or on a piece of paper and every one of those games define the interaction players can have with other players and the environment.
Creating a game revolves around making sure those rules create a coherent game play.

## Video games

In video game development a lot of the creative processes that what we've talked about so far are used the same way but has a different steps.
We can see a game as a movie generator where each action of the player can change the video playing in real time. Since games are programs that reacts to player inputs it needs to be concealed in a ...

### Game loop

Let's change our movie step process to better fit what a game does in real time.

![video game](Game.png)

<!-- 1. Design, assets creation and game logic programming (this is where the game development happens)
2. Game Loop (this is where the game runs)
   1. Read player input
   2. Game logic
      1. Run scripts
      2. Run physics simulation
   3. Rendering
      1. Draw visible elements on the screen.
      2. Apply effects
      3. Post processing
   4. Repeat -->

### The tools

### What stride offers