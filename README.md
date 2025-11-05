# Node.js Command-Line-Quiz-Game
A basic interactive quiz application built with Node.js that runs directly in your terminal. 
Test your knowledge with multiple-choice questions!




✨ Features
Loads questions from a questions.json file.
Presents a specified number of random questions.
Prompts the user for their answer (by entering the number corresponding to the choice).
Validates user input.
Checks answers and outputs true for correct or false for incorrect.



# 🚀 How to Run
Follow these steps to get the quiz running on your local machine:



# Prerequisites
Make sure you have Node.js installed. You can download it from nodejs.org.



# Installation
Clone the repository (or download the code directly)

Bash
git clone <your-github-repo-link>
cd <your-repo-name> # e.g., cd simple-nodejs-quiz
(Replace <your-github-repo-link> with the actual link to your repository once you create it on GitHub. Replace <your-repo-name> with the name you give your repository.)




# Install dependencies:
This project uses prompt-sync to get synchronous user input.

Bash
npm install
(This command will install all dependencies listed in package.json. If you don't have a package.json yet, you might need to run npm init -y first, and then npm install prompt-sync.)

Usage
To start the quiz, simply run the project.js file using Node.js:


Bash
node project.js
The quiz will present a question, and you'll need to enter the number corresponding to your chosen answer.



# 📁 Project Structure

project.js: The main application logic for the quiz.
questions.json: (You'll need to create this file) 
Contains the quiz questions, options, and correct answers. 



# 🛠️ Built With

JavaScript
Node.js
prompt-sync (npm package for synchronous user input)


