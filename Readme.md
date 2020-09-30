# Assignment

Hello and welcome to your assignment! In this document I'm going to lay out the objectives, and some ground rules.
This test is primarily to test your ability to set up and start working on something in Vue with Typescript. You will be using some very basic wireframing images to guide your design of the interface, though styling-wise it's up to you to be creative.
 
# Technologies
The following technologies must be used:

- Vue 2+
- Typescript

Other than the above your more than welcome to use anything that you think might make this task simpler, better or more production ready.

# Submission Requirements
This assignment should take no longer than 4 hours, though feel free to take a little longer if it's required. If you're uncertain about anything during the assignment let us know, and we can try to provide some guidance.

- Firstly you should fork or clone this repository to your own account and all work should be done alongside the files here (were expecting to see a professional commit history).
- The code that you submit should be considered production ready, submissions which keep this in mind often come across better.
- Try to avoid using any for your typescript definitions, we expect to see properly constructed type safety everywhere.
- The final solution must work and run, please provide setup instructions if it's not already clear how to run the code.
- We have provided some extra space below the assignment under notes here if you'd like to you can make some notes about the assignment or any of the decisions you made.

Finally, once you think you've finished the assignment please send a link to a publicly accessible repository, so our team is able to take a look over the code

# The Assignment

In this assignment you will be producing three separate pages that all have separate challenges linked to them (Don't worry there quite simple) each challenge attempts to test your ability at something different from the other.

### Initial setup:

1) You must bootstrap a new Vue application, we don't mind how you choose to do this.
2) You must setup routing to have the following:

- /challenge-1
- /challenge-2
- /challenge-3

By default, when the application loads we are expecting `/challenge-1` to be present.

### Challenge 1

You are required to produce a small calculator that takes two values in btc using this format: `0.00000000` and adds them together. Using the result of this calculation the result will be displayed. Following uses of this calculator will take the last value calculated and add it to the previous one. It shouldn't matter if a user enters a string or number, special charchters or negative numbers aren't supported and should stop the calculation from being run.

Don't worry too much about visuals with this, focus on making the code behind the scene's work well.

### Challenge 2

You are required to add a button, and a heading below which says 'My Boxing Area'. When the button is pressed below the heading a box should appear with no more than 100px of height and should initially take up the majority or all of the page width. Subsequent pushes of this button will add another box to the same row, and the 100% of the width will be taken up by the two boxes each with 50% of the toal row width each. Continuing to press this button will carry on adding new boxes that take up more of the space and causes the existing boxes to be reduced in size. When the total number of boxes reaches 8 subsequent presses should create a new row and all new boxes should be added to this row with the same effect as above.

Try and make it clear and simple to see different boxes inside the rows, bonus points if it works responsively.

### Challenge 3

You are required to add a localization feature to this page. You are required to add an input and a dropdown and a button with the text 'GO' written inside. The Input should only allow string input. The Dropdown will have `EN` and one other language of your choosing (as an example for dutch we could put `NL`). When a user enters a string and selects a language you will be required to match it against an entry inside a separate json localization file, and the result should be printed out underneath our form.