# Kilovolt Blog Lab 10
 
**Author**: Ramon Mendoza and Jeremy Crawford
**Version**: 1.0.0
 
## Overview
This product is designed to give users a consistent reading and navigation experience across mobile and desktop devices, with content ordered by most recent first and sortable by both author or category. Additionally, users who want to add articles to the blog with the submit button. The articles are now available via a database instead of just from local storage.
 
## Getting Started
 
The user would need to
 * Create index.html
 * Get the icons from IcoMoon (including all related files and CSS).
 * Get the normalize.css from github.com/necolas/normalize.css.
 * Search and find images of bacon, baseball, and cats
 * Add filler text.
 * Build CSS files according to SMACSS methodology.
 * Include link to jQuery library (CDN).
 * Create the articles as objects within an array with consistent property values.
 * Create a constructor function to make the article array accessible to the constructor's method.
 * Use jQuery to access and clone HTML elements of the DOM and populate those elements with content from the article array.
 * Create forEach loops to generate new object instances and then append them to the DOM.
 * Create an array of objects to hold the content generation for the DOM for each object.
 * Create a JS file to generate a more interactive view of the DOM (selecting authors, catagories and hiding/showing full articles as well as navigating the long page as if it was a multipage website).
 * Add Handlebars library and use it to create a tempalte for the HTML articles.
 * Add the Higlight JS library and related CSS styling to have the ability to highlight content.
 * Create a new HTML page to handle article submissions that offers a form to create an article and ability to preview content.
 * Connect the new HTML page to the exisiting blog page and update articleView.js, as well as articles.js to render content correctly across both pages.
 * Be sure to write DRY code and leverage the libraries, as well as arrow functions to make code work as optimially as possible.
 * Regularly use console logs, Chrome developer console tools and the help of others to identify and correct all coding and rendering erros.
 * Convert the blogArticle.js to JSON file, hackerIpsum.json
 * Next the user will need to install two npm packages including Express and nodemon, fs, bodyparser, pg. 
 * The user needs to be sure to create a proper .gitignore file
 * Change all functions to arrow functions where possible and contextual this is not used.
 * Install postgreSQL to your system.
 * Create a kilovolt database.
 * Write SQL queries to connect the database to the controller for use by the view.

## Architecture
 
We used IcoMoon icon font for navigation icons. We included the jQuery, Handlebars, Hightlight JS, and Railcasts libraries, with related CSS as needed. We installed and used Express, pg, fs and nodemon npm JS packages. We installed and used postgreSQL. We worked to create a RESTful website application. We used Chrome, and nodemon to analyze and inspect the view and the controller. We used the postgreSQL shell to check model. Project is built used HTML, CSS, JavaScript, Node and SQL.

 
## Change Log
02-26-2018 0900am - committed new file structure including Ramon-Jeremy directory
02-26-2018 1000am - all code has been successfully wrapped in an IIFE
02-26-2018 1230pm - initial effort compelted, code is not fully functional.commited nearly complete query work
02-26-2018 0300pm - code is fully functional and merged to master
02-26-2018 0330pm - README.md complete, code merged to master.
 
## Credits and Collaborations
 * Thanks to our instructors and TAs and our classmates, with special thanks to Nick.
 * The following libraries were used: jQuery,Highlight JS, Handlebars and Railcast.
 * We referenced the jQuery cheat sheet: https://oscarotero.com/jquery/
 * We used HandleBars library.
 * We referenced our text book: Jon Duckett - JavaScript and JQuery.
 * We used Node documentation: https://nodejs.org/en/
 * We referenced the SQL Language cheat sheet througout our work that was provided by our instructor.