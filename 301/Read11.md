# 301 - Read11 

## EJS 

**What is EJS used For**

EJS is used for applications that require quick templating, it is very easy to setup and does the job well. EJS let's us spin up quick applications when we don't need anything too complex. By using partials and having the ability to easily pass variables to our views, we can build some great applications quickly.

**Install EJS** 

$ npm install ejs

**Use EJs**

let ejs = require('ejs');
let people = ['geddy', 'neil', 'alex'];
let html = ejs.render('<%= people.join(", "); %>', {people: people});


## Working with Volumes 

### Performing a search

GET request to the following URI:

**https://www.googleapis.com/books/v1/volumes?q=search+terms**

This request has a single required parameter:

**q** - Search for volumes that contain this text string. 

*special keywords you can specify in the search terms to search in particular fields :*

- intitle: Returns results where the text following this keyword is found in the title.
- inauthor: Returns results where the text following this keyword is found in the author.
- inpublisher: Returns results where the text following this keyword is found in the publisher.
- subject: Returns results where the text following this keyword is listed in the category list of the volume.
- isbn: Returns results where the text following this keyword is the ISBN number.
- lccn: Returns results where the text following this keyword is the Library of Congress Control Number.
- oclc: Returns results where the text following this keyword is the Online Computer Library Center number.


**Request**

Here is an example of searching for Daniel Keyes' "Flowers for Algernon":

**GET https://www.googleapis.com/books/v1/volumes?q=flowers+inauthor:keyes&key=yourAPIKey**