# Stardew fisher
Fishes for me in stardew valley because I am lazy.

This project was made as a basic showcase of opencv image capturing and template matching.
I would have liked to write this in C#/.NET, but I only had access to my laptop which contains a 32gb drive with flash memory, and almost all of that is windows. So, python it is.

The problem I chose to approach is Stardew Valley fishing. Why? Because it's simple enough to run off a flash drive, 2D, and a 1-dimension problem. All are factors when considering I have no internet, so this is all on my knowledge plus what I can grab off my phone's internet.

The basic idea is shown in the picture below: keep the fish icon in the green bar, and you'll slowly catch the fish. If the fish escapes, you'll slowly lose the fish.

![Image of Idea](https://github.com/mrmattkennedy/Stardew-Fisher/blob/master/video%20screenshots/gif-screenshots/25.jpg)

So I set off to create this incredible AI to change the world, with my limited resources.
Currently, the opencv aspect is completely done in python. When I get access to the world again, I'll remake this in .NET with opencv, and work on a q-learning algorithm to try and make this smarter. Reason for q-learning is that this is a tricky learning curve, even if the problem is simple: pressing the mouse slowly moves the bar faster and faster, there is momentum and gravity to consider, so I believe a reinforced learning method would be best to let the algorithm figure it out "for itself".

Current progress displayed below. This is what the algorithm sees (notice the blue boxes when the fish escapes the green bar. These are to identify the position of the fish, and the position of the bar.)
![Image of Idea](https://github.com/mrmattkennedy/Stardew-Fisher/blob/master/video%20screenshots/what_algorithm_sees.gif)

(I know this gif has about 1 frame per second. This is because this laptop was not meant to do image analysis and run steam games simultaneously).
