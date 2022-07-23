# Rock paper scissors

This is a project for the Odin Project to create a simple rock paper scissors game. 

When the game() function is called, the user is prompted to enter a guess: rock, paper, or scissors. The computer also generates a random guess, and the two guesses are compared to determine the winner of a five-round game.

For the user's guess, capitalization doesn't affect the outcome since .toUpperCase() is used to convert the user's guess to compare with the computer's guess, which is all-caps by default. So, a user can enter rock, Rock, RoCk, or another variation and no difference is made.