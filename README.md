## Setting up Locally

* Install [docker](https://www.docker.com) and docker-compose on your system.
* Install `psql` for your system which is a client for the Postgresql database.
* Go the root directory of the system
* Run `docker-compose up --build`
* After the containers are up and running , run `psql -h 127.0.0.1 -d flamup -p 5432 -U postgres -c "\copy clothes FROM 'data2.csv' DELIMITER ',' CSV";`.

Now continue to https://localhost:8443, the application should be up and running.

