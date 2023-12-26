This tool was created using ChatGPT to assist with the editing and creation of 'sprite' data in the M16 protogen firmware. 

This tool can take an array of checkboxes and output a binary array for use in the firmware. There is also the option of taking
the binary array and running it back into checkboxes to make editing easier.



Sprites:

The firmware draws different segements of the Protogen face from the users selection. Jaws, Nose, Eyes, OWO Eyes, Annoyed/Angry Eyes,
Dead Eyes, OWO Jaw, Annoyed/Angry Jaw, and Dead Jaw. 

Each sprite has a fixed length, and may have additional 'frames' if the portion is animated.
For example, the eyes blink, but are not animated, the blink animation is a canned manipulation of one sprite.
Whereas jaws can have up to 5 frames depending on which emotion is being presented.

Sprite Info:

Eye:
1 8x8 Sprite, drawn on both sides of the visor


Nose:
2 8x8 Sprites, sprite is drawn on each side of visor, second sprite is an animation frame (Nostril flare for breathing)
To set a static nose (no breathing) the second sprite will be a duplicate of the first

WIP
