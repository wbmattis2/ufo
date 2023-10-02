# UFO  

Simple hangman-style game made by Benny Mattis with C++ to specifications provided in a Codecademy project  

## How to Use  

Compile and run ufo.cpp, and follow the prompts in your command line interface to play the game.  

Note: this program was built with version 11 of C++, and you mmay need to specify this when compiling to avoid errors.  For example, most Mac users will be able to compile the program without warnings by navigating to the directory in Terminal and entering `clang++ -std=c++11 ufo.cpp`.  

## Object of the Game  

ASCII art portrayed over the course of the game depicts a person being abducted by aliens. The object of the game is to guess the mystery word before the person is abducted. They can save the abductee by guessing the mystery word.  

The player can guess letters by entering them as input; each letter will either appear in the mystery word (if the mystery word contains that letter) or among the letters that are not contained in the mystery word.  

Every time the player guesses a letter that is not part of the mystery word, the abductee gets pulled up further by a UFO's tractor beam. Once the abductee is pulled all the way up to the space ship, the game is over. If all of the letters in the mystery word are guessed, then the abductee is saved!  

## Starter Code from Codecademy  

The definition and declaration of `display_misses()` were pre-written and included by Codecademy in starter files for this project, which also included namespace inclusions and an empty `main()` function.
