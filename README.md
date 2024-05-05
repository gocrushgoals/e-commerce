# e-commerce

## Description

 View walkthrough: https://drive.google.com/file/d/1WRAypq7d9a9d9HzkZtUK3apbr_Fs8LhL/view?usp=sharing 



## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
Mock-Up

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation
Clone the code from Github at https://github.com/gocrushgoals/e-commerce

## Usage

Initialize the application by sourcing the seeds by using the terminal command "npm run seeds" 
Connect the server by using the terminal command "node server.js"
Use a program like Insomnia or Postman to run the get, post, put, and delete routes to modify the products, tags, id, and categories. 
You can reference the routes in the /routes folder to see commands available.

## Credits
Source Code From Edx Bootcamp: https://github.com/coding-boot-camp/fantastic-umbrella 
OSU coding bootcamp classes
OSU tutors
MDN Web Docs
NMP Documentation

## License

See the repository for licensing information.
