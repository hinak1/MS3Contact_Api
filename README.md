# contact-api
Python Rest API. Supports full CRUD operations and also incremental updates. 


## Overview
This server was written by Hina Kanwal for MS3. This server supports Full CRUD operations and also incremental and full updates. 
This server uses Python Flask Module. Includes Swagger / Open API  based documentation / client. Also includes postman test collection
## Requirements
Python 3.5.2+</br>
pip3</br>
refer to requirements.txt for list of modules to be installed
## Usage
To run the server, execute the following from the root directory:
```
pip3 install -r requirements.txt</br>
cd app </br>
python app.py </br>
```

and open your browser to here:

```
http://localhost:5000/api/v1/contacts?limit=1
```

Your Swagger definition lives here:

```
http://localhost:5000/api/v1/swagger/
```

## Running with Docker


To run the server on a Docker container, please execute the following from the root directory:

```bash
# building the image
<<<<<<< HEAD
$ docker build -t docker-flask:latest .

# starting up a container
$ docker run --name flaskapp -v$PWD/app:/app -p5000:5000 docker-flask:latest
=======
docker build -t swagger_server .

# starting up a container
docker run -p 8080:8080 swagger_server

```
# Testing
Import the postman collection in postman client.
Postman collection file is placed in \MS3Contact_Api\PostmanTestCollection folder
Test collection contains requests for all operations with default request parametres