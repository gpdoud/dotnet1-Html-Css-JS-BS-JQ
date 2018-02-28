Bowling in JavaScript

* Create an HTML page (bowling.html)
* Add JavaScript code (<script lang="javascript">)
* Add a JavaScript function called PlayBowling()
* Inside the PlayBowling function:
  * Create a variable of type array and init as empty
  * Create a for() to iterate 10 times for each of the 10 frames
  * Inside the for() loop
    * Get a random number between 0 and 10 inclusive
    * Store the random number in the array
  * When the for() loop is done.
    * Turn the array into a string using Join(",")
    * Display the string using console.log(stringname);
* Without jQuery
  * On the <body> tag, add the OnLoad event
    <body OnLoad="PlayBowling()">
* Extra:
  * Tally all the frames to produce the game score
  * Console.log the frame and game scores using Join