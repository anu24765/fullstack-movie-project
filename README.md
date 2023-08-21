# Fullstack Movie Project

This is a fullstack movie project that includes various functionalities related to user accounts, movie management, reviews, and more. The project is developed using PHP, HTML, CSS, and MySQL.

## Project Structure

The project consists of the following files and directories:

- **useraccount.php**: This file handles user account information and profile.
- **updateaccount.php**: Allows users to update their account details.
- **searchmovies.php**: Enables users to search for movies in the database.
- **reviews.php**: Manages movie reviews, listing and displaying them.
- **registration.php**: Displays a registration form for new users.
- **register.php**: Processes user registration and adds new users to the database.
- **processMovie.php**: Handles movie-related operations and updates.
- **movies.php**: Displays a list of movies from the database.
- **moviedetails.php**: Displays detailed information about a specific movie.
- **logout.php**: Logs out the currently logged-in user.
- **loginform.php**: Displays a login form for users.
- **login.php**: Handles user authentication and login.
- **index.php**: The main landing page of the application.
- **deleteuser.php**: Deletes a user account from the database.
- **deletereview.php**: Deletes a movie review.
- **deleteMovie.php**: Deletes a movie entry from the database.
- **createreview.php**: Displays a form to create a new review for a movie.
- **addtoaccount.php**: Adds a movie to the user's account.
- **addreview.php**: Adds a user review for a movie.
- **addmovie.php**: Allows administrators to add new movies to the database.
- **includes**: Directory containing reusable code snippets.
- **db**: Contains database-related configuration and scripts.
- **assets**: Directory for storing CSS, images, and other static assets.

## Installation and Setup

1. Clone this repository to your local environment using:
    git clone https://github.com/yourusername/fullstack-movie-project.git

2. Create a MySQL database and import the required database schema using the SQL scripts provided in the `db` directory.

3. Update the database connection details in the necessary files within the `includes` directory or wherever applicable.

4. Ensure that your environment meets the requirements for running PHP and MySQL.

5. Start a local server or deploy the project to your web server to access the application.

## Usage

- Register a new user account using `registration.php`.
- Log in using `loginform.php`.
- Browse movies and view their details on `movies.php` and `moviedetails.php`.
- Search for movies using the `searchmovies.php` page.
- Add movies to your account using `addtoaccount.php`.
- Leave reviews for movies using `addreview.php`.
- Administrators can add new movies using `addmovie.php`.
- Update your account details on `updateaccount.php`.
- Delete your account or reviews using `deleteuser.php` and `deletereview.php`.
- Log out using `logout.php`.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
