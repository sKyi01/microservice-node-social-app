# Social Media App

This social media application is built with Node.js, Express, and MongoDB. It allows users to create an account, post updates, and interact with other users' posts. The app also includes authentication and authorization features using Passport.js.

## Table of Contents

* [Features](#features)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Technologies Used](#technologies-used)


## Features

* User authentication and authorization (local, JWT, and Google OAuth2)
* Create, edit, and delete posts
* Comment on posts
* Upload user avatars
* Responsive design with Sass
* Email service integration

## Prerequisites

Before you begin, ensure you have met the following requirements:

* Node.js (v12 or higher)
* MongoDB
* npm (Node Package Manager)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/sKyi01/social-media-app.git
    cd social-media-app
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Set up your MongoDB database:
    - Make sure MongoDB is running on your local machine or update the `mongoUrl` in the session configuration to point to your MongoDB server.

4. (Optional) Set up environment variables for production:
    - Create a `.env` file and add your environment-specific variables.

## Usage

1. Compile Sass files:
    ```sh
    npm run sass
    ```

2. Start the server:
    ```sh
    npm start
    ```

3. Open your web browser and go to `http://localhost:8080` to access the app.


## Technologies Used

* Node.js
* Express.js
* MongoDB
* Mongoose
* Passport.js (local, JWT, and Google OAuth2 strategies)
* EJS (Embedded JavaScript templating)
* Sass (Syntactically Awesome Stylesheets)
* Connect-mongo (session store)




