[Open](https://leo-antonio-auhagen.github.io/Leo-Antonio-Auhagen/)

# What is this?
Ever wanted to play an analog wordle?

Enter a five letter word to get the encoding functions for that analog wordle game.

Rules:

**1.** Letters are encoded by their position in the alphabet: **'A' is 1 and 'Z' is 26**.

**2.** Functions green_*n*(x) give you the encoding for the letter at position *n*: <br> => position *n* is green if and only if green_*n* for the entered letter is 0.

**3.** Function yellow(x) gives you the encoding for all yellow letters: yellow(x) is 0 whenever the letter is present somewhere in the word.
NOTE: A letter that is green at a certain position is yellow at all positions.
                
