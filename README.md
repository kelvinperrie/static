# static
testing methods of how to make something look like static on a webpage

 * static-canvas.html - a canvas where the pixel colours are changed to a random selection of black or white. This mostly works but can be a bit jerky. Performance might improve if using multiple js loops to do the updating from black/white.
 * static-dom.html - a collection of dom elements (divs) where the background colour of the elements is updated to a random selection of black or white. This requires a ridiculous amount of divs but actually works pretty well provided you don't want the pixel size of the static to be too small.
 * static-gif.html - putting a gif (of static) as the background image. Seems to work best and is the most straight forward. Requires an image but no JS. Hardest part is getting a gif, which I made from the first tests.

![Example 1](howdyFolks.gif?raw=true "howdy folks example")
