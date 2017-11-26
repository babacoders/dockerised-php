A Simple Docker setup for PHP applications using PHP7-FPM and Nginx 

## Instructions

1. Open up http://play-with-docker.com on your browser

2. Checkout the repository

* git clone https://github.com/babacoders/dockerised-php

3. Run Docker Compose CLI

* Run `docker-compose up`

4. Navigate to the below URL

* Navigate to localhost:8080

That's it! You have your local PHP setup using Docker

This displays an image of minions on the web browser.

# Adding a Simple Website

5. Clone this simple PHP Web Page under the dockerised-php folder

* git clone https://github.com/babacoders/simple-php-website

6. Move the simple-php-website folder to code folder

* mv simple-php-website code

7. Restart the Docker Compose

* docker-compose restart

8. Navigate to the browser again. You will see Simple PHP Webpage
