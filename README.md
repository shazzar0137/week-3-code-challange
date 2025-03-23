# week-3-code-challange
# Movie Theatre Web App
This project is a simple movie theatre web application that allows users to browse through a list of films, view details of selected films, search for movies, and buy tickets.
# Table of content
Features
Installation
File structure
Usage
Technology Used
License
# Features
# Film List: Displays a list of movies fetched from a server.
Search Functionality: Allows users to search movies by title.
Movie Details: Displays details of a selected movie, including the title, poster, runtime, showtime, and available tickets.
# Ticket Purchase: Users can buy tickets for a movie, and the available tickets are updated dynamically.
Installation
Prerequisites
A modern web browser (e.g., Chrome, Firefox, Edge).
Setup Steps
Clone this repository:

git clone git@github.com:shazzar0137/week-3-code-challange.git
cd wk3-codeChallenge
Install json-server globally if not already installed:

npm install -g json-server
Start the json-server with the provided db.json file:

json-server --watch db.json
Open the index.html file in your browser to view the app.

File Structure
wk3-codeChallenge/
├── index.html       # Main HTML file
├── style.css       # Styling for the app
├── index.js        # Main JavaScript file
├── db.json          # JSON database for movies
└── README.md        # Documentation file
Usage
Viewing Movie List:

The sidebar displays a list of movies fetched from the server.
Click on a movie to view its details in the main content area.
Searching for Movies:

Use the search bar in the header to filter the list of movies by title.
Buying Tickets:

Click the "Buy Ticket" button to purchase a ticket.
If tickets are sold out, an alert will notify the user.
Technologies Used
HTML5: For structuring the app.
CSS3: For styling and layout.
JavaScript: For interactivity and dynamic content.
json-server: To simulate a backend for fetching movie data.
Customization
Styling:

Modify styles.css to change the appearance of the app.
Data:

Edit db.json to add, remove, or modify movie details.
Behavior:

Update index.js to implement additional functionality or adjust current behavior.
Known Issues
Tickets do not persist across sessions. This could be resolved by adding server-side updates.
Future Enhancements
Add user authentication for ticket purchases.
Integrate a real backend with a database for persistent data.
Display additional movie details such as ratings and reviews.
License
This project is licensed under the MIT License. See the LICENSE file for details.