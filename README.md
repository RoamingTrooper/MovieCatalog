Project Task: Movie Catalog Website
Objective:
Create a movie catalog website where users can browse and discover movies. This project will assess the learners' understanding of HTML, CSS, and JavaScript, with an emphasis on creating an attractive user interface and implementing interactive features.
Requirements:
Movie Listing:
Display a grid or list of movie posters with titles and release years.
Include pagination or lazy loading for browsing multiple pages of movies.
Movie Details:
Create a separate page or modal for displaying detailed information about a movie.
Include movie title, poster, synopsis, genre, director, cast, and rating.
Search and Filter:
Implement a search feature allowing users to search for movies by title, genre, or cast.
Provide filters to refine search results by genre, release year, or rating.
Responsive Design:
Ensure the website is responsive and works well on various screen sizes (desktop, tablet, mobile).
Use CSS media queries to adapt the layout and styling accordingly.
Project Structure:
HTML Structure:
index.html: Main HTML file containing the structure of the movie catalog website.
movie.html: HTML file for displaying detailed information about a movie.
CSS Styles:
styles.css: CSS file for styling the HTML elements and layout.
JavaScript Interactions:
script.js: JavaScript file for implementing interactive features such as search functionality, filtering, and dynamic content loading.
Example Functionalities:
Movie Listing:
<div id="movie-grid">
 <!-- Movie posters will be dynamically generated here -->
</div>

Search and Filter:
<input type="text" id="search-input" placeholder="Search movies">
<select id="genre-filter">
 <option value="">All Genres</option>
 <!-- Populate genre options dynamically -->
</select>
<button onclick="searchMovies()">Search</button>

function searchMovies() {
 const searchTerm = document.getElementById("search-input").value;
 const selectedGenre = document.getElementById("genre-filter").value;
 // Perform search operation and update movie grid
}

Movie Details:
<div class="movie-details">
 <h2>Movie Title</h2>
 <img src="movie-poster.jpg" alt="Movie Poster">
 <p>Synopsis:</p>
 <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit...</p>
 <p>Genre: Action</p>
 <p>Director: John Doe</p>
 <p>Cast: Actor 1, Actor 2, Actor 3</p>
 <p>Rating: 8.5/10</p>
</div>

Evaluation Criteria:
HTML Structure: Is the HTML well-structured with appropriate use of semantic elements?
CSS Styling: Are the CSS styles effectively applied to create an attractive layout and design?
JavaScript Interactions: Are interactive features implemented smoothly with JavaScript?
Responsive Design: Does the website adapt well to different screen sizes?
Example Workflow:
Creating HTML Structure:
Define the structure of the movie catalog website using HTML elements such as <header>, <nav>, <section>, <footer>, etc.
Styling with CSS:
Apply CSS styles to the HTML elements to define the layout, colors, fonts, etc.
Adding Interactive Elements with JavaScript:
Implement JavaScript functions to handle interactive features like searching, filtering, etc.
Testing and Refining:
Test the website on different devices and screen sizes to ensure responsiveness and functionality.
Refine the design and functionality based on feedback.
By completing this project, learners will demonstrate their proficiency in HTML, CSS, and JavaScript, as well as their ability to create a visually appealing and interactive web application for browsing movies.

