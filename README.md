## Project Setup Guide

### Cloning the Repository

1. Open a terminal or command prompt.
2. Navigate to the directory where you want to clone the project.
   ```sh
   cd /path/to/your/directory
   ```
3. Clone the repository using Git:
   ```sh
   git clone https://github.com/KMSoe/next-movie.git
   ```
4. change directory into the project directory:
   ```sh
   cd project_name
   npm install
   ```


### Environment Configuration

Create a new `.env` file and set API key token from [www.themoviedb.org](www.themoviedb.org):
   ```sh
   TMDB_TOKEN=
   ```

   And replace the database credentials.


### Running the Application

   ```sh
    npx next
   ```

The project should now be up and running! <br/>
Access it via `http://localhost:3000` or the port you run in your browser.