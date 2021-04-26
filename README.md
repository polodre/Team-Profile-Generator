# Team-Profile-Generator

## Description

This is a Node.js command-line application that takes in information about employees on a software engineering team, then generates an HTML webpage that displays summaries for each person.

When the app is launched, the user is prompted to describe the first team member. The user enters the team member's name, and selects one of the following roles: "Engineer", "Intern", and "Manager" . The user is also prompted to enter the member's ID, email address, then must enter another piece of information based on what role was selected. If "Engineer" is selected, the user is prompted for the team member's GitHub username. if "Intern" is selected, the user is prompted to enter the members school, lastly, if "Manager" is chosen, the user is prompted for the team member's phone number.

- This is an example of prompts when the application is started:
  ![Answered Questions](/images/image1.PNG "Answered Questions")

When the new team members info has been entered, the user is asked if they would like to add any additional members. If yes, the user is prompted with the same questions. If not, an HTML file is created with cards displaying the team members information that was entered in the user located in the "outputs" folder, titled "team.html." A screenshot of an example team profile is shown below:

![Team Members](/images/image2.PNG "Team Members")

## Techniques / Technologies Used

- NPM
- Jest
- FS
- Inquirer
- HTML
- JAVASCRIPT

## Link to video demonstrating the app:

https://vimeo.com/541878590/3279fd7c3a

## Team Profile Generator on GITHUB:

https://polodre.github.io/teamProfileGenerator/
