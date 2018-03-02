# 3rd .Net Boot Camp

## SimpleCraps program

Included in this respository is the SimpleCraps program written in JavaScript.

When I did this, there will be a couple of things in the source code that may not be familiar to you, but this was not the only way to achieve the goals of the program.

The FirstRoll() function returns an object - This function handles all the work for the first roll in the game. It determines two things: A) whether the player won or lost, and B) if neither, what is the point number. Because a function can return only a single item, but that item has to both indicate whether the play won or lost and the point if needed.

I chose to do that with an object. The first key indicates whether the game is done. If true, the second key indicates whether the play won or lost. If the first key indicates the game is not over, the second key provides the point number.

I will provide a full explaination on Monday. You can, as always, send me a message on Slack and I'll respond over the weekend as soon as I can.

See you all Monday which starts the second half of the boot camp.

Time flies ...