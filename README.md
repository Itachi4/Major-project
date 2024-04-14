# Movie Recommendation System

## Project Overview

This repository contains a full-stack Movie Recommendation System that offers personalized movie suggestions using machine learning techniques. The system features an Angular-based front-end for a dynamic user experience and a Node.js/Express back-end for efficient API management.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Features](#features)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Authors](#authors)
- [Acknowledgments](#acknowledgments)

## Technologies Used

- **Angular**: Front-end framework for building dynamic, responsive user interfaces.
- **HTML, CSS, JavaScript**: Core technologies for web development.
- **Node.js**: JavaScript runtime built on Chrome's V8 JavaScript engine.
- **Express.js**: Web application framework for Node.js, designed for building web applications and APIs.
- **Pandas & NumPy**: For data manipulation and operations within the Node.js environment (or consider a Python microservice if used).
- **Scikit-Learn**: For implementing machine learning algorithms (consider using a Python-based service if necessary).
- **MongoDB**: NoSQL database used to store user data and movie information.
- **Heroku**: Platform as a service (PaaS) that enables developers to build, run, and operate applications entirely in the cloud.

## Setup and Installation

To get this project up and running on your local machine, follow these steps:

```bash
# Clone the repository
git clone https://github.com/Itachi4/Major-project.git
cd Major-project

# Install backend dependencies
npm install

# Serve the Angular application
cd angular-app
npm install
ng serve

# Run the Node.js server
cd ..
node server.js

## Features

- **User Authentication**: Manage sessions and user authentication using Node.js and Express.
- **Movie Ratings and Reviews**: Allows users to rate and review movies, which influences the recommendation logic.
- **Real-time Recommendations**: Dynamically suggests movies based on user interactions and preferences.
- **Interactive UI**: Built with Angular for a seamless and engaging user experience.

## Usage
- After setting up, access the front-end of the application by navigating to http://localhost:4200 and interact with the back-end via http://localhost:3000. Utilize the application to browse movies, submit ratings, and get personalized recommendations.
