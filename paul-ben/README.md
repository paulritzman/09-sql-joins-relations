# Kilovolt Blog

**Author**: Paul Ritzman, Ben Taylor
**Version**: 1.0.0

## Overview
This application is a blog, which communicates with a local server via Node.js and a backend SQL database.

## Getting Started
* Use SMACSS design philosophy to create a modular layout.
* Utilize Responsive Web Design techniques.
* Use JQuery and Object Oriented programming methodologies to append blog postings to the DOM.
* Use AJAX and local storage to load data and render articles on the page.
* Install Node and Express via npm
* Initialize the server and all dependancies
* Direct server to PSQL database.

## Architecture
* HTML5
* CSS3
* JQuery v3.3.1
* AJAX
* npm v5.6.0
* Node v9.9.0
* Express v4.16.3
* Postgresql v10.3
* SMACSS/RWD design principles
* IcoMoon icons

## Change Log
05-18-2018 9:09am - Initial repo setup.

05-18-2018 9:11am - All dependancies installed, package-lock.json created.

05-19-2018 9:18am - Set conString. Fixed indentation issue.

05-19-2018 9:37am - Added TODO items to server.js; Completed SQL query within app.get('/articles').

05-19-2018 9:45am - Completed SQL query within app.post('/articles').

05-19-2018 9:57am - Modified SQL query within app.post('/articles') to do nothing on conflict; Completed SQL query for queryTwo() function.

05-19-2018 10:35am - Finished app.post functionality.

05-19-2018 10:53am - Finished app.put functionality.

05-19-2018 10:57am - Finished CRUD testing.

## Credits and Collaborations

* Oscar Otero - [JQuery Quick API Reference](https://oscarotero.com/jquery/)