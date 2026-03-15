## Intro
This discusses the steps I took for this project. I ran the docker locally on my system for this assignment

## Frontend
- Here I created a dockerignore file
- I created a Dockerfile
- The docker file can be mentally put into parts:
  - The first part deals with building the project and adding the variables
  - The second part deals with copying the built project into a folder we created in the first part

## Backend
- Here I adjusted the env file so that the database url aligns with the one to be created in the docker compose file
- I also create a Docker file and a docker ignore file

## Docker Compose
- This was created in the Frontend root folder. I know this isn't ideal but I did it anyway
- The yaml file had 3 services: Frontend, backend, database
- I exposed the environmental variables to be used which were stored in the frontend env. Yea I know it is not ideal, it was 3 am.
- I ensured that the backend doesn't run until the database is ready

