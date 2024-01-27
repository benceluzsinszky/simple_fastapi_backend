# Simple FastAPI backend

A FastAPI backend with a PostgresSQL database.


## Requirements
This game was built using Python 3.12.1. 

To install the requirements use:

`pip install -r requirements.txt`

## How to use
Clone the repository or download the code files.

To run the code locally:

`uvicorn main:app --host 0.0.0.0 --port 8080 --reload`

The repository includes a `docker-compose.yml` file, to build and run the server with the docker compose:

`docker-compose up --build`


The server can be accessed on: 

`http://localhost:8080/`


The docker-compose is set up, so that if any change is saved in the files it automatically updates the container and restarts the server.
