## UTA Bootcamp Challenge 13

In this homework assignment from the University of Texas-Austin Bootcamp we were asked to create an application for managing an online shop. Starter code was provided and we were given the task of correctly connecting the routes to the database server.

# Online Store Routes
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

Building this app gave me the opportunity to learn about routes that connect API database servers to a javascript application.

## Table of Contents

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

- You will need to instal MySQL and Node.js if you have not already done so.

Be sure after downloading and unzipping the directory to run in your integrated terminal or command prompt in the appropriate directory:
- ```npm i```
- Update your password and username in the .env file.
- Navigate to the db folder with ```cd db```
- Log into MySQL with ```mysql -u root -p```, and enter your password.
- In MySQL, run ```SOURCE schema.sql```
- Log out of MySQL, then return to the root directory with ```cd ..```
- Seed the local database with ```npm run seed```
- Make the simulated local server go live with ```npm start```


## Usage

Once the program is operating in the terminal, you may use an application such as Insomnia to test the various routes.

Here is a provided Mock-up GIF of the desired functionality:
    
![Bootcamp Provided GIF](./assets/13-orm-homework-demo-01.gif?raw=true)
    

Demo video:

https://www.loom.com/share/3f9a31736ddc499082b5a5e27983e9ea

## Credits

Thanks to fellow students in this bootcamp adventure:

- Chris Zavala https://github.com/chrisZavala

In particular, Chris' example of a PUT route and the code he passed on from tutor Meg Meyers to fix the broken starter code for the PUT request example were super helpful!!!

## License

Copyright 2023 Joshua Goeke

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


## Attributions:


This README.md is patterned off of an example at https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide
