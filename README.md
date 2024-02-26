# laravel-exercise
Build API gateway using Laravel framework. I am using PostgreSQL for the database and I want to build migrate system to create the database if there is no table in the database. For the deployment, I am going to build a docker image.

**Create the database**
We can use docker to create the database here is the comment to pull the image:
```
docker pull postgres
```
and to create a database use this command:
```
 docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres
```
you can see more detail here: https://hub.docker.com/_/postgres

**Laravel Installation**
