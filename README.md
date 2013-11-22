ece2524_final_project
=====================

Asylum Amnesia

contributors: jpenn92, cmpadden, mp1138
url: https://github.com/cmpadden/ece2524_final_project

This project is a text based adventure game.  The player wakes up in an asylum with no memory and must figure out
what events have happened by exploring rooms and using objects to solve puzzles.  We may also implement a combat
system in our game.

One design philosophy we look to follow is the Rule of Modularity.  We plan to write the game in a way so that it
can be expanded in the future.  For example, the game will output text, but by using different modules for the
game algorithm and the game text interface, a GUI could easily be added over top of the game in the future to 
enhance the user experience.  Also, by making the program modular, it will make the task of programming less of a
headache because it is much easier to work with several small modules as opposed to one large module that contains
all of the program's code.

Additionally, we plan to follow Ken Thompson's other Unix Philosophy of code being easily maintained and extend-able.
The maintenance portion of this philosophy will be implemented by thoroughly commenting the code in such a way that 
future developers will fully understand why we made the decisions we did during the design process. The extendability
aspect of this rule will be achieved by giving developers the ability to implement more rooms for the user to traverse
while exploring the Asylum. This will make it so the game could be ever-growing; adding additional features for the
game-player.
