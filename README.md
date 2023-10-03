# Mongoose Movies
Mongoose Movies is a CRUD web application used to help track and manage your favorite movies along with their cast.

This is a CRUD app built with Express, Express Generator, and Mongoose, designed specifically for managing movie information and reviews. It allows users to add, view, update, and review movies stored in a database.

# Features

Add new movies with title, release year, and cast information.
Display all movies in a table.
Allow users to leave reviews and ratings for movies.

# Prerequisites
Node.js and npm should be installed on your machine.
MongoDB should be installed and running.

# Getting Started
Clone the repository:
git clone https://github.com/your-username/movie-db-reviews.git
cd movie-db-reviews
Install the dependencies:
npm install
Configure the database connection:

Open the config/db.js file.
Update the MongoDB connection URL if necessary.
Run the application:

npm start
Open your browser and visit http://localhost:3000 to access the app.
Usage
To add a movie:

Click on the "Add Movie" link in the navigation menu.
Fill in the required details (title, genre, release year, director).
Click the "Add Movie" button to submit the form.
To view all movies:

Click on the "All Movies" link in the navigation menu.
The movies will be displayed in a table.
Click on the table headers to sort the movies based on the respective column.
To review a movie:

Click on the "Details" button next to the movie you want to review.
Fill in the review details (rating, review).
Click the "Add Review" button to add your review.

# Technologies Used
Express.js: Fast, unopinionated, minimalist web framework for Node.js
Express Generator: Express application generator
Mongoose: MongoDB object modeling for Node.js
HTML, CSS, JavaScript: Front-end development

# License
This project is licensed under the MIT License.
