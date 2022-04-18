# Project 2: Pixel Station

## About
Pixel Station is an art sharing site for pixal art where users can created a account with a proile picture, create posts with images, comment on posts, and view other user's galley while editing/deleting their own posts to curate their profile page. There is also an admin login where they can view all users, posts, and delete users/posts as part of running the site.

## Start Up
The project consits of a backend and a frontend that must be run seperatily at the same time for the website to function. The backend uses the Maven package manager and needs to be be updated/built with Maven to get the depencies. The application.properties file must also be edited to connect to a database of your choice. The project has driver support for MySQL, PostgreSQL, and H2 by default. Then run the backend as a Spring Boot app listening on localhost, port 8090.
The frontend is an angular app that after running npm install to get the node packages, it is recommended to run the frontend with the Angular CLI which can be installed using npm as well. The Angular project needs to run on port 42000 or the crossorgin annotitation on the controllers in the backend must be updated to let the frontend addresss connect to it. Once both backend and frontend are running, going to the Angular app website and register your first user to begin.
> NOTE: Admin accounts must be created by editing the isAdmin boolean of a user in the database the backend is connected to.
