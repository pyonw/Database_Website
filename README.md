JobReady: Your Ultimate Job Preparation Tool

Authors: Woo Pyon, Salim Jalaleddine

Overview

JobReady is a web-based database application designed to help computer science graduates prepare for software engineering jobs. With features to store and manage information about interview questions, classes, projects, and internships, JobReady empowers users to track their readiness for job interviews. It also allows companies to assess potential candidates by evaluating their preparation through data structures and algorithm practice.

Features

User Management: Create, search, update, and delete user profiles.
Question Management: Manage interview questions, including their difficulty and associated links.
Class Management: Track classes taken by users and their relationships to users.
Project Management: Store details about user projects, including descriptions, languages used, and GitHub links.
Internship Management: Track user internships, including company names and dates.
Search and Dynamic Update: Easily search for and update user data through dynamic forms and dropdowns.
Database Schema

Entities
Users: Stores user profiles including name, language, university, GPA, location, and LinkedIn profile.
Questions: Stores interview questions, including the problem description, difficulty level, and link to the problem.
Classes: Tracks classes that users have taken.
Projects: Stores details about user projects.
Internships: Records internship details for users.
Relationships
1
Relationships:
Between Users and Classes
Between Users and Projects
Between Users and Internships
M
Relationships:
Between Users and Questions
Between Users and Classes
ER Diagram and Schema

The project uses a well-structured entity-relationship model and schema to ensure the integrity and efficiency of the data.

Sample Data

Here are some examples of the kind of data managed by JobReady:

Users:
John Doe: Python, Javascript, Harvard, GPA 4.0
Sammy Smith: C++, MIT, GPA 3.9
Stacee Lopez: C, Javascript, CSS, HTML, Oregon State, GPA 3.5
Questions:
Two Sum: Easy, Link
Trapping Rain Water: Hard, Link
Snakes and Ladders: Medium, Link
Classes:
Data Structures
Web Development
Algorithms
Projects:
Battleship Game: Python, GitHub Link
Tetris Game: C++, GitHub Link
Full Stack Website: Javascript, CSS, HTML, GitHub Link
Internships:
Red Fruit: 05/25/2016 - 09/10/2016
Rainforest: 10/15/2012 - 02/10/2012
Checks: 05/11/2015 - 09/11/2015
UI Screenshots

Users: Display, Create, Search, Update, Delete
Questions: Display, Create, Search, Update, Delete
Classes: Display, Create, Search, Delete
Projects: Display, Create, Search, Update, Delete
Internships: Display, Create, Delete
Users Questions: Display, Create, Search, Update, Delete
Users Classes: Display, Create, Delete
Getting Started

To run this project locally:

Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/jobready.git
Install dependencies:
bash
Copy code
npm install
Set up the database using the provided schema and sample data.
Run the development server:
bash
Copy code
npm run dev
Open http://localhost:3000 to view it in the browser.
Contributions

We welcome contributions! Please submit a pull request or open an issue for any improvements or suggestions.

License

This project is licensed under the MIT License. See the LICENSE file for more details.
