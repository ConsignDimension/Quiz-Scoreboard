Pub-Quiz-Scoreboard
===================

A simple (currently a bit hacky) pub quiz scoreboard written in JQuery

Note, some of the code (especially the CSS) was done last minute and is a bit hacky, so please excuse poor quality!
Subpit a pull request if you have any suggestions or improvements.

Summary
====

There are two main "screens" and three different types of scoreboard.
On the home screen there are two scoreboards:

 - Team Scores - you enter the scores in each round here, you can edit the text directly
 - Live Scoreboard - this automatically updates any time you edit the scores to show the latest positions
 - Popup Scoreboard - this shows the scores in each round with forward/backward buttons

Demo 
====

You can play with a [live demo here](https://rawgithub.com/Pezmc/Pub-Quiz-Scoreboard/master/index.html), or view the video of the scoreboard below.

[![ScreenShot](https://raw.github.com/Pezmc/Pub-Quiz-Scoreboard/master/images/pubQuizYoutube.png)](http://youtu.be/Fu2zBQlXqpA)

Todo
====

The following are features I would love to add:

 - Step Throuch Popup Scoreboard one at a time - only updating one team in reverse order for more suspense
 - Having a popup of the live scoreboard
 - Replace the hacky and rushed CSS for the popup window
 - Encapsulate the different scoreboards -> `$('#live').liveScoreboard($dataTable)` etc...
 - ~~Swap table.js functions so you could call `$('#table').save('teams')`, `$('#table').load('teams')`~~
