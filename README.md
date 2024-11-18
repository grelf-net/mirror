This is a further development of my 3D program "The Green", demonstrating the usefulness of plain Javascript with a 2D canvas.

This version has a vertical mirror and it is possible to go "Through the Looking-Glass", Alice-style. The first attempt to create this, in Spring 2021, was not very successful because the mirror slowed the action down far too much.

Now (November 2024) I have managed to optimise the mirror processing significantly and I have added various new features in order to submit it to the Portland creative group's <a href="https://itch.io/jam/finishyourgamejam2024">"Finish Your Game"</a> Jam.

There are several features referencing Lewis Carroll's original story. The player is invited to discover them by wandering around. Clicking on objects often makes things happen. Going through the mirror reveals more things, notably some chess queens in various colours. The behaviour of the queens is at first weird and the player may spend some time trying to see what is going on. It involves tri-stimulus colour both in a visual sense and with a nod to sub-nuclear physics!

A side issue I have included in this version is using speech synthesis to speak as well as display textual hints. I was surprised to discover from <a href="https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API">MDN</a> how easy it is to do this from Javascript. Expecting the synth to pronounce "icosahedron" correctly was understandably a step too far though: listen out for it. (I use Windows and mainly Firefox so I hope it works on other platforms.)

I was intending to make the player's objective to be capturing the red queen (when she is not hiding) and bringing her back through the mirror - to some kind of surprise. However, I have been unable to come up with any ideas for how the player might do that. So I throw this out as a challenge: can any creative person see how to complete the development along those lines?

I am putting the source files on <a href="https://github.com/grelf-net/mirror/">github</a> too, for anyone to try adding that further development. (There is no money involved. This is just a hobby. I am keen to encourage creativity.)
