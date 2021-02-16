# Movify
A dynamic, social networking web application for movie enthusiasts who want to journal, share, and categorize their movie interests. 

## Technologies Used
- React.js
- Node.js
- Express.js
- PostgreSQL
- multer
- Babel
- AWS EC2
- Webpack
- Bootstrap 4
- reactstrap

## Features
- User can sign in, create an account, and log out.
- User can search for movies or users of the app.
- User can view the details of a movie (including synopsis, reviews, similar movies).
- User can view, create, or delete a custom list.
- User can add or delete a movie from a custom list.
- User can view, add, or delete movies from their favorites or watch list.
- User can view, create, delete, or update their reviews of a movie.
- User can view, send, and delete messages from other users.
- User can edit and view their own profiles and view other users' profiles (including uploading their own profile image).
- User can sort and filter movies by different genres & categories.

## Live Demo
Try the app here: https://movify.kevinnhim.com

If you don't want to make an account, use this test one:

Username: cody@gmail.com

password: coding

## Development

### System Requirements
- Node.js
- npm
- PostgreSQL
- Express.js

### Getting Started
1. Clone the repository:
```shell
git clone https://github.com/knhim/movify.git
cd movify
```

2. Install dependencies with NPM:
```shell
npm install
```

3. Start PostgreSQL server:
```shell
sudo service postgresql start
```

4. Create the database
```shell
createdb movify
```

5. Copy the .env.example file and update with your PostgreSQL credentials
```shell
cp .env.example .env
```

6. Import the database schema: 
```shell
npm run db:import
```

7. Start the app:
```shell
npm run dev
```

8. View application locally:
```shell
http://localhost:3000
```



