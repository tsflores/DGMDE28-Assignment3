# DGMDE28-Assignment2b
The next step towards the completion of the Tic Tac Toe game for Harvard Extension School course DGMD E-28

URL: https://trinidads-portfolio.com/DGMDE28/Assignment2b/ttt3.html

For this version of the assignment, I modified the HTML / CSS / Javascript code in the following way:
1.) Moved the Div's that were used to create an indication of the player's turn and game status to withing the wrapper (container) class.  These were then created using JavaScript document.writer vs. having them sit outside of the script
2.) Adjusted the CSS to properly style the player's turn and game status to align at the bottom of the grid
3.) Added an event listener to each game square with 'click' functionality.  A click would place an 'X' in the appropriate square and alert the user to the action

Reflection question: Careful planning of the structure of the HTML can assist with identifying selectors in both CSS and Javascript.  How do you think the structure of ttt3 helps or does not help with that goal?

Reflection answer: The structure of tt3 includes a series of Div's that divided the page into 11 areas (9 for the game board and 2 for the comment boxes).  By using a series of Div's, we can apply a class and unique ID to each square of the game board.  The board could have been created through an application of Grid in CSS - simply dividing a section on the page into a desired row-column layout.  However, it would have been more difficult to access individual squares within that structure.  The individual Div's with unique IDs allowed me to apply an event listener to each square.  By doing so, I can manipulate content, style, etc... or keep track of where I am on the board.  For example, I could use the structure to change the color of an X vs. an O by applying a different CSS rule to the appropriate selector or ID.  As we implement the remaining features of the game, this will be an important aspect to create an efficient solution.
