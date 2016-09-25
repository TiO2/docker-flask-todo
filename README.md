WARNING: THE CODE HERE AND LINKED LIVE DEMO ARE LIKELY VERY OUT OF DATE.

docker-flask-todo
-----

This is a learning example using docker to package up a flask todo application that uses mongodb.

## Tutorial

This code was used to do a live tutorial demo [here](https://www.youtube.com/watch?v=6opltZu4ABw)


## change history:
Folked repo, tested on Digital ocean on 20160924.  
1. updated mongodb image to 3.2  
2. the docker-compose file link db: environment variable name changed to 'DB_PORT_27017_TCP_ADDR'.   
However, note that according to the documentation: https://docs.docker.com/compose/link-env-deprecated/ , the environmental variable will be depreciated. 
>Note: Environment variables are no longer the recommended method for connecting to linked services. Instead, you should use the link name (by default, the name of the linked service) as the hostname to connect to. See the docker-compose.yml documentation for details.


Todo:  
1. versioning: Compose file format, Version 1 and Version 2. COnsider to use version 2.   Done.  
2. add travis-ci




