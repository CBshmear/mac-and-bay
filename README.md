# mac-and-bay

## Description
This repo contains all the code for a fully functioning backend of a small e-commerce site. I wanted to design an api that follows RESTful practices. It stores product, category and tag data using mysql and sequelize models. I ran into some difficulties building the models and properly assigning foreign keys but got it all squared away. Through those challenges i learned alot about sequelize model structure.
## Installation
To install the necessary packages, run "npm I" in your terminal.
## Usage
Here is a link to a walkthrough video of the app using insomnia to test:  https://drive.google.com/file/d/1Ci8G7WDXhw8j_gNeEpynMEFzaS58Ih4n/view

To initiate the database, log into mysql and source the schema file to create the database. After that, exit mysql and seed the database by running the command "npm run seed" in your terminal. Once the database is seeded, initialize the application with the command "node server.js" to begin listening.
## Credits
I referenced the sequelize documentation frequently 
https://sequelize.org/docs/v6/

## License
The MIT License (MIT)
Copyright © 2023 Connor Beer

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
