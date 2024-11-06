# Cricket-Score-Keeper-App
Cricket Score Keeper
The Cricket Score Keeper is a simple React application that allows users to input the name and marks (score) of players. Submitted entries are added to a list, displayed in a table format. This app provides an easy interface to keep track of cricket scores, or it can be repurposed for any other scoring activity.

Features
Add a player's name and score (marks).
Display the list of players and scores in a table.
New entries appear at the top of the list.
Clear the input fields after each submission.

Getting Started

Prerequisites
You need a browser that supports JavaScript and a basic setup for serving HTML files locally or online.

Running the App
Clone this repository to your local machine.
Open the index.html file in your browser to run the app.

File Structure
├── index.html     # Main HTML file with React setup and script
├── style.css      # Optional CSS file for additional styling
└── README.md      # Project information

Code Explanation
index.html
The main HTML file includes:

React and ReactDOM: Loaded via CDN links in the <head> section.
Babel: Included to allow inline JSX in <script type="text/babel">.

App Components:
Form: Contains two input fields (for name and marks) and a submit button. Uses React.createRef() for managing input references.
Result: A table that displays the list of students and their marks.
App: The main component that renders both Form and Result components.

Functions
addStudent: A function that captures the input values, validates that both fields are filled, and pushes the data into the students array. It then re-renders the App component to update the display.
clearInputs: Clears the name and marks input fields after each submission.

Example Usage
Enter a name in the "Name" field.
Enter the score in the "Marks" field.
Click the "Submit" button, and the entry will appear in the table below.

Technologies Used
React: JavaScript library for building user interfaces.
Babel: JavaScript compiler for using JSX.

Future Enhancements
Store player scores in localStorage to retain entries after page reloads.
Add an edit and delete option for each player entry.
Include score validation to allow only numerical input for marks.

License
This project is open-source and available under the MIT License.
