# Upload-CSV


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>

## About The Project

User can upload the csv files from their own system. the Application shows the data of CSV file in Tablel format and where user can also perform some operations.
Tech Stack : HTML, CSS, JS, Node.js

### Features :

-  Upload any csv file into the system (consider the delimiter to be a comma ‘ , ’) [If you don’t know
   what’s a csv, download the other file in this folder and take a look at it, then google a little more]
-  Display a list of all uploaded csv files
-  When the user selects a file, display all the data (with column headers) in a table on the page (front
   end)
-  There should be a search box which searches on the front end itself and displays the matching rows
   of the table only (empty search box displays all the data). (you can put a search on any one column)
-  DIFFERENT CSV FILES WITH DIFFERENT COLUMN HEADERS CAN BE UPLOADED,TABLE HEADERS SHOULD BE DYNAMIC
-  Sorting button (ascending and descending) for each column on the front end
-  Put a validation on the front end and server side on being able to upload only csv
   type of files
-  Pagination of the data displayed in the table to a max of 100 records per
   page

### Built With

Here is the Technology Stack of this Application. which I have used to Built this Application.

-  MongoDB
-  Express
-  NodeJS
-  HTML
-  CSS

<!-- GETTING STARTED -->

## Getting Started

-  Clone this project
-  Start by installing npm and mongoDB if you don't have them already.
-  Run the Mongo Server.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

-  npm
   ```sh
   npm install npm@latest -g
   ```

### Installation

1. Clone the repo

2. Install NPM packages
   ```sh
   npm install
   ```
