# PLANET LHL

## Midterm Lighthouse Labs Group Project

By Aaron Bolarinho, Kevin MacArthur, Erica Sabo, and Carlos Cadiz

Hello and Welcome!

### Overview

This midterm project was the first major project group project for lighthouse labs students (then three weeks into the course).

This project challenged the students to put together everything they had learned in the first three weeks; that being principally:

 - Javascript
 - Node.js and server-side middle-ware
 - Knex; a back-end database structure
 - Html, Css, and basic front-end formatting
 - Basic CRUD operations

**Planet Lighthouse Labs**

This website project was modelled loosely on a Pintrest design, where users would browse, create, and share internet resources relating to our Planet Earth.

On the main page, users can browse through all resources added by users and follow those links, like, and comment on those resources.

Once a user registers and logs in, the user can go to their profile page.

On this profile page, the user can browse all general resources that the user has previously liked or commented on, as well as create new resources (which, when added, will appear in the general collection on the main page). The user can also search their collections by added keywords, and change their password.

Creating a single resource involves adding into a form the resource url (for example, [https://en.wikipedia.org/wiki/Fish](https://en.wikipedia.org/wiki/Fish)), adding a title, a comment, and some searchable keywords.

The two highlights of the project were:
 - an Image-Scraper which automatically finds the major image from a given resource link and displays it
 - Flying white CSS birds that continually travel underneath the title of the main page.

The four group members of this project had around 4 days to complete it; we all had fun and were proud of our final product - it was amazing what we could do from zero at course start to three weeks in!

### The Main Page
![""](https://github.com/AaronBolarinho/PlanetLHL/blob/master/docs/Screenshot%20from%202019-06-07%2015-34-57.png)

### The User Page
![""](https://github.com/AaronBolarinho/PlanetLHL/blob/master/docs/Screenshot%20from%202019-06-07%2014-08-23.png)

## Getting Started

1. Install dependencies: `npm i`
2. Fix to binaries for sass: `npm rebuild node-sass`
3. Run migrations: `npm run knex migrate:latest`
  - create table into an existing database midterm
4. Run the seed: `npm run knex seed:run`
5. Run the server: `npm run local`
6. Visit `http://localhost:8080/`
7. Register as a user with username and password to have access to our nature-learning site!

## Dependencies

- AOS 2.3.4 or above
- Body-parser 1.15.2 or above
- Bcrypt 2.0.0 or above
- Bootstrap 4.1.3 or above
- Cookie-session 2.0.0-beta.3 or above
- Dotenv 2.0.0 or above
- EJS 2.4.1 or above
- Express 4.13.4 or above
- Knex 0.15.2 or above
- Knex-logger 0.1.0 or above
- Metascraper 4.4.4 or above
- Metascraper-image 4.3.5 or above
- Metascraper-title 4.3.5 or above
- Morgan 1.7.0 or above
- Node-sass-middleware 0.9.8 or above
- PG 6.0.2 or above
- Uuid 3.3.2 or above
- Node 5.10.x or above
- Nodemon 1.9.2 or above
- NPM 3.8.x or above
