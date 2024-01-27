# Guess_the-_state

U.S States Game using Turtle Graphics
This Python script is a simple interactive game that utilizes the Turtle graphics library to help users learn and quiz themselves on U.S states. The game displays a map of the United States with the states' names initially hidden.

How it works:
The game loads a blank map of the U.S using the image "blank_states_img.gif" as a background.

The list of all 50 U.S states is read from a CSV file named "50_states.csv" using the Pandas library.

The user is prompted to guess the names of the U.S states one by one. The program keeps track of the guessed states.

If the user enters the name of a correct state, the script uses the Turtle graphics library to create a turtle at the location of that state on the map and displays the state's name.

The game continues until the user guesses all 50 states or decides to exit by typing "Exit." If the user exits, the script saves the names of the states not guessed in a CSV file named "missing_states.csv."

Dependencies:
Python
Turtle graphics library
Pandas library
