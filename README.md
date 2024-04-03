# jeoparody
How to use it:

1. Copy the jeoparody.html file to a local hard disk drive.
2. Open the file in a browser, and wait for the app to load.
3. Once loaded, the intention is to alternate between Team 1 and Team 2 by allowing the current team to pick a category and value.
4. Once the card is selected the card is clicked, and the hint is displayed, and the team whose turn it is gets to give an answer.
    1. From the hint screen multiple options exist:
        1. Show the answer
        2. Award the team that guessed the answer correctly
        3. Award no one
        4. Undo any action.
        5. "Done" will simply take you back to the main board.
    2. The intended play style is to let the answer be guessed by the opposite team in the case that the team whose turn it is gets it incorrect. The idea would be to let both teams; starting with the team whose turn it is, render an answer, and then only after both teams lock in their anaswer, click the button to show the answer. If the first team gave an acceptable response then they should be awarded the points, and if they were incorrect, but the second team was correct, they can take the points. In the case that niether team had an acceptable answer, the points are lost. (you might want to flip this order to give the advantage to the team whose turn it is, or have a nuetral 'host' who accepts the answers in secret).
5. Once the above step is done, click "done" to return to the board where the next team gets a turn, steps 3-5 are repeated until all cards are removed.

# warning!
All progress is erased as soon as the browser page is refreshed! There is no back-end server, the game is completely browser based.

# notes
The team names can be changed by clicking on them. They will persist as long as the browser is not refreshed.
If you know JSON, you can edit the html file as text, and keep the formatting intact, but change the questions, answers, values and categories to make whatever form you would like. The JSON that exists there came from a random selection of real questions from the show this project was modeled after. 
