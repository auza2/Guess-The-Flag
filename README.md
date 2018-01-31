# Guess-The-Flag
<img src="https://media.giphy.com/media/3ohs4mk9TtJLSgYbWE/giphy.gif" width="244" height="480" />

# Description
This is a small game in which the user has to pick which flag belongs to the country name that appears on the navigation bar at the top. The flags were given as additional files for the project and I learned that you can use the same file name with an @1x, @2x, or @3x to indicate the different sized pictures which is useful for the varying sizes of devices. AutoLayout was used again to keep the flags in the middle of the screen by choosing the Center Horizontally constraint as well as the contstraint to keep the y position. All the flags were UIButtons and I learned that to keep the size of the button the same, you should put in the image before trying to use Auto Layout because it will just morph your button into any size it wants. They all went to the same IBAction which checked to see if the answer was correct and changed the score accordingly. The flags and answer were picked using the GamePlayKit with arrayShuffling and sharedRandom methods. Whenever an answer was picked a UIAlertController was presented with an action element attached with the title "Continue?". This is where I learned something new, this method had a handler parameter which is the method that is called when the action element is pressed which is called a closure. It's very similar to a lambda expression in other languages.

I also learned that all UI elements have a core animation layer that takes care of rendering and this is where we can change the border width and border color of the UI button. 

*Project 2 of Hacking with Swift Tutorial*
