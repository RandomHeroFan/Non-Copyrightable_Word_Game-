Welcome to the Non-Copyrightable Word Game! Another version of New York Time's hit game!

To play the game Player One creates a word which has five letters in it,
Player Two is given six chances to get the word correctly.
The games goes until the word is guessed or all chances have been used. 

To further explain this, let’s assume the word chosen by player 1 is ‘React’.
As the second player you can choose any word with five letters in it. Let’s pick ‘Route’. 
After choosing this word you would end up seeing

----
R - Green
O - Red
U - Red
T - Yellow
E - Yellow
---- 

Each of the letters represent different parts of the puzzle. 

Red,    That letter is not in the word. 
Yellow, That letter is in the word but in a different space. 
Green,  That letter is in that exact correct position.

Using this information you could guess the next word is ‘Reset’.
From this you would get

---- 
R - Green
E - Green 
S - Red
E - Red
T - Green
----

Here is a special case where you can see that ‘E’s are both green and red
this is because there is only a single ‘E’ in the answer and so the other one is red.
With all this information your final guess may be ‘React’ 

in this case you will see 

---- 
R - Green
E - Green
A - Green
C - Green
T - Green
----

at this point the game will be over and you will be prompted to play again.


The project was created within 24 hours and holds a few notable bugs such as 

the fact that a word can be made up of numbers
&&
A word can which has multiples of the same letter may be given false information

Although I didn't get to fix every bug and I didn't add every feature I wanted,
I am proud of what I ended up making within this time limit.
