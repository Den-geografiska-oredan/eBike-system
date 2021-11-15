# Electric Scooter System

This the main repository for the project electric scooter system. 
The project is a part of the course frameworks & designpatterns @ Blekinge Institute of Technologies.
If you would like to know more about the course you may find some information here [dbwebb.se/ramverk1](https://dbwebb.se/kurser/ramverk1-v2).

## Running with Docker

### Backend
At the moment the backend can be started via docker-compose with the following command:
    docker-compose up -d ebike_backend

The flag -d starts the container in the background. Omit this if you want to see the server running in your console.

After starting the backend is exposed on port 8000. To verify in a browser use url: http://localhost:8000/api/.

To rebuild the docker container after making any changes just add the --build flag like:
    docker-compose up -d ebike_backend --build


This project consists of several parts. For more information about the individual parts checkout their repositories.  
* [Backend Laravel](https://github.com/DMoest/eBike-backend-laravel)  
* [Frontend React](https://github.com/DMoest/eBike-frontend-react.git)  
* [WebbApp React](https://github.com/DMoest/eBike-webbapp-react.git)  
* [Control System Python](https://github.com/DMoest/eBike-controlsys-python.git)


### The team in this project:  
Daniel Andersson  
Robert Israelsson  
Robin Granqvist  
Sofia Herelius  
