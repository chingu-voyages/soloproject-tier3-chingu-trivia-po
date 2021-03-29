# Chingu Solo Project - Tier 2 - Chingu Trivia - for Product Owners

## Overview 

As a Product Owner this project is a great opportunity to demonstrate your organization skills to help a team who will develop this clean and modern webpage. 

You are currently on the **Tier 2 repo** and this Solo Project is only for Product Owners **not** Developers. You'll be responsible for creating User Stories and Tasks from the requirements listed below.

As you increase your Product Owner skills and experience you'll be able to come back to this project and enhance it for the Tier 3 version. Ultimately you'll have a great portfolio piece to share with interviewers.
## About Chingu

If you aren’t yet a member of Chingu we invite you to join us. We help our 
members transform what they’ve learned in courses & tutorials into the 
practical experience employers need and want.

Our remote team projects let you refine your technical skills and put them 
into practice while gaining new “soft” skills like communication, 
collaboration, and Agile project management. The types of skills that 
help real-world teams get things done!

You can learn more and join us at [chingu.io](https://chingu.io).

## Instructions

General instructions for all Pre-Work Projects can also be found in the Chingu Voyage Handbook (URL posted in the `#read-me-first` channel on Discord). You can also find more information about the User Stories [here](https://docs.chingu.io/projres/agile101#building-the-backlog)

Your task for this Solo Project is to create Users Stories and/or tasks for 
[Requirements](#requirements) below.
Feel free to add questions or additional comments in the User Stories that you 
feel would be helpful to team members working on it.

You may create your User Stories and tasks as text file or in the tool of your choice (like ZenHub, Notion, Trello, etc.). Remember that you don't neet to worry about technical details. What's important is to demonstrate your ability to create a set of tasks a team could follow to build the app.

#### Requirements

*Structure*

- [ ] Header item that includes the name for the app, and tabs (if using)
- [ ] Card that displays a trivia question and four multiple choice answers
- [ ] Place element that displays which question number the user is on and the total number of questions (ex. 'Question 1 / 10')
- [ ] Display buttons for advancing to the next question once the current question has been answered
- [ ] Display a message to the user that informs them if their answer was right or wrong
- [ ] Display a clear message to the user when the trivia session is done, and include the user's score

*Styling:*

- [ ] Styles should be reminiscent of the demo versions. Feel free to use artistic licencse as long as the functionality doesn't suffer 

*Functionality*

- [ ] The quiz should span all questions in the question api (see below for api information)
- [ ] The page should not reload!
- [ ] Questions are received from the api at the following address: *https://johnmeade-webdev.github.io/chingu_quiz_api/trial.json*
- [ ] The api is static and does not take in parameters or require a key, simply make your fetch to the above address

*Upon Load:*

- [ ] Load the first question and display the user's place as *Question 1 / 10*
- [ ] Make sure the button used to advance questions is either not visible or not clickable until an answer is submitted

*Considerations:*

- [ ] Try and style your app so that it doesn't overflow the viewport (require scrolling) on any device
- [ ] Make sure your User Experience design is intuitive (buttons are clearly disabled when not available, messages are clear, etc)
- [ ] In the name of responsiveness: please try and have your answer buttons (or divs, or whatever you use) collapse into a column in small sizes (iPhone5, etc)

## Example

![](./assets/chingu_trivia.gif)
