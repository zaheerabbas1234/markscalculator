Exercise 4:
Module name :Implementation of CICD with Java and open source stack
Configure the web application and Version control using Git using Git commands and version control
operations. 


Grade Generator Web Application
Overview
The Grade Generator is a simple web application that allows users to input their marks in three programming languages: Java, Python, and C. The application calculates the total and average marks based on the input provided. It is designed to be user-friendly and provides immediate feedback on the user's input.

Features
Input fields for student name and marks in Java, Python, and C.
Calculate total marks.
Calculate average marks.
Displays the results dynamically on the page.
Technologies Used
HTML: Structure of the web application.
CSS: Styling of the web application.
JavaScript: Functionality for calculating total and average marks.
Getting Started
To set up and run the Grade Generator web application locally, follow these steps:

Prerequisites
A modern web browser (e.g., Chrome, Firefox).
Basic knowledge of HTML, CSS, and JavaScript (optional for running the app).
Installation
Clone the Repository
If you have Git installed, you can clone the repository:

git clone https://github.com/yourusername/grade-generator.git

Navigate to the Project Directory
Open your terminal and navigate to the project directory:

cd grade-generator

Open the index.html File
Open the index.html file in your web browser. You can do this by dragging the file into the browser window or right-clicking and selecting "Open with" followed by your browser choice.

Usage
Input Fields: Enter your name and the marks obtained in Java, Python, and C.
Calculate Total: Click on the "Total" button to see the total marks displayed.
Calculate Average: Click on the "Average" button to see the average marks displayed.
File Structure
/grade-generator
│
├── index.html # Main HTML file
├── style.css # Styles for the application
└── script.js # JavaScript file for functionality

Code Explanation
HTML (index.html)
Contains a form for user input.
Input fields for student name and marks.
Buttons for calculating total and average marks.
Divs for displaying results.
CSS (style.css)
Styles the background, input fields, buttons, and results.
Uses flexbox for alignment and spacing.
JavaScript (script.js)
Selects DOM elements for user input and result display.
Handles total and average calculations using event listeners on buttons.
Updates the DOM with calculated results.
Example
<!-- Example input for Java --> <input type="number" placeholder="Marks in Java out of 100" class="java" required />
Basic Git Commands
Here are some basic Git commands that can be useful for version control:

Setup
Initialize a new Git repository: git init
Set your Git username and email: git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
Version Control Operations
Check the status of your repository: git status
Add files to the staging area:
git add <filename> # Add a specific file
git add . # Add all changes
Commit changes with a message: git commit -m "Your commit message"
View commit history: git log
Create a new branch: git checkout -b new-branch-name
Switch to an existing branch: git checkout branch-name
Merge branches: git merge branch-name
Push changes to the remote repository: git push origin branch-name
Pull the latest changes from the remote repository: git pull origin main
Contributing
If you'd like to contribute to the project, please fork the repository and submit a pull request with your changes. Make sure to follow the coding standards and include relevant tests.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
MDN Web Docs for HTML, CSS, and JavaScript resources.
Inspiration from various web development tutorials.
Feel free to copy and paste this text into your README file!

Here are 10 basic Git commands that are essential for version control:

git init
Initializes a new Git repository in the current directory.

git clone [repository URL]
Creates a copy of an existing Git repository from a remote location.

git status
Displays the current status of the working directory and staging area, showing which files are modified, staged, or untracked.

git add [file]
Stages changes to a specific file for the next commit. Use git add . to stage all changes.

git commit -m "[message]"
Commits the staged changes to the repository with a descriptive message.

git log
Shows the commit history for the current branch, including commit IDs, authors, dates, and messages.

git branch
Lists all branches in the repository. You can use git branch [branch-name] to create a new branch.

git checkout [branch-name]
Switches to the specified branch in your repository.

git merge [branch-name]
Merges the specified branch into the current branch.

git push origin [branch-name]
Pushes commits from the local branch to the specified branch on the remote repository.

These commands form the foundation of basic Git usage and are useful for tracking changes and collaborating on projects.
