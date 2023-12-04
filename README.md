# DataCollectorDocker

When trying to dockerise the DataCollector API, I created a Dockerfile, nuilt the image and run to create the container, after all that worked, i created a dockercompose.yml file to make the two services:the frontend and API communicate with each other.
But when running the dockercompose.yml file, the frontend service was running on the corresponding port and the API was running but the data was not being shown, to test it, i used postman to check the connection to the api and it was working fine. So the error was in showing the data from the api into the frontend.

##  Run the dockercompose file 
Open terminal and run the following command:
     docker compose up

##  Stop the docker compose 
In the powershell go to the directory of the dockercompose file and run the following command:
     docker-compose down
