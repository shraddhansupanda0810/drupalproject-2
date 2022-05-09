
## Getting Started

### Requirements

* git
* docker
* docker-compose

## Setup Drupal application Locally


### DockerCompose

1. Cloning the GitRepo

   ```
   git clone 
   ```

2. Creating an .env file
   ```
    MYSQL_ROOT_PASSWORD=<root_password>
    MYSQL_DATABASE=<drupal>
    MYSQL_USER=<drupal_database_user>
    MYSQL_PASSWORD=<drupal_database_password>
   ```

3. Setting up application

    Building docker image of the code from your local i.e code inside docroot.
        Just run the docker-compose command.
    <br><br/>

   Command :

   ```
   docker-compose up -d
   ```

4. View the application on <http://localhost:90>

<br></br>

### Debugging Issues

  ```
  docker exec -it <imagename> 
  ```
  
<br></br>

## Note

  Deployment of drupal application on kubernetes and helm can be found here.
  <https://github.com/>
  
  <br></br>
