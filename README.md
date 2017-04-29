# PHP dev boilerplate for Docker

## How to use

Create a `.env` from env-template in ./env using the following command:

```
cp ./env/env-template ./env/.env
```

You can change the environment config of the for the docker setup inside the .env file, any time.

Then simply type:  

```
docker-compose up
```

Thats it. The boilerplate is running. Now place your php files inside the `./app` folder, and browse for them.


Enjoy.

# Configuration

The environment can be configured within the **.env** file, which is a prerequisite to run the application.  
To create this, copy or rename the **env-template** file to **.env**.

## Constants

### APP_PATH

Defines the relative or absolute path to the application you desire to run.

### ENV_PATH

Defines the path of the docker container configuration.

### DATA_PATH

Defines where persistent data should be stored. Right now, this is used for mysql only.

### MySQL Constants

These constants are prefixed with **MYSQL_**, followed by database, username, password, port, etc...
