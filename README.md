# Shape Shifting Gameplay Mechanic[^1]
The mechanic in its current state functions by using a Data Asset that contains an array of the player forms struct.
This struct contains a form ID (string) and a form (class reference to a child class of the PlayerBase BP).
When the player Shape Shifts (using the F key) **it cycles to the next player form within the array.** 
The Player stats struct is basic struct containing a Health (float), MaxHealth (float), Attack (float), and Player State (enum).
Player state currently holds no function other than some possible examples. *However*, please feel free to entirely remove this if you desire.
**The main mechanic that must persist in at least some form is the Shape Shifting mechanic**

[^1]: This is a part of a templated game jam
