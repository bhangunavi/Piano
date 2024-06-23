HTML Structure:

A <div> with the class piano acts as the container for the keys.
Each key is represented by a <div> with the class key. Additional classes white and black differentiate between the white and black keys.
The black keys also have specific classes (black-1, black-2, etc.) to position them correctly over the white keys.
CSS Styling:

The body is styled to center the piano on the screen.
The .piano class uses display: flex to lay out the white keys in a row.
Each .key has a border to simulate the edges of the keys.
.white keys have a fixed width and height, and a white background.
.black keys are shorter in height and slightly narrower than the white keys. They are positioned absolutely within the .piano container using the position and left properties.
Each black key is positioned correctly relative to the white keys using the specific left values in the .black-n classes.
