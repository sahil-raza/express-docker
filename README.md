![Node.js CI](https://github.com/hammadkhokhar/express-docker/workflows/Node.js%20CI/badge.svg) [![Maintainability](https://api.codeclimate.com/v1/badges/055992c8756b80cdf19c/maintainability)](https://codeclimate.com/github/hammadkhokhar/express-docker/maintainability)
# express-docker  
NodeJS Express app for docker which can be used in AWS fargate.

---
## Requirements

  - For development, you will only need Node.js and install packages by running package.json

  - Local testing with docker requires docker installed and running before build and run

  - For aws fargate, you will need additionally AWS CLI.

## Running the project without Docker

    $ node bin/www
    
Go to http://localhost:3000 in your browser to see the app.    
    
## Running the project with Docker

    1. Build using terminal or cmd:
    $ docker build -t my-docker-app . 
    
    2. Build using terminal or cmd:
    $ To test it simply run 'docker build -t my-docker-app .' and then 'docker run -it -p 3000:3000 my-docker-app'. 
    
Go to http://localhost:3000 in your browser to see the app.

  - Open issue if any problems.

    
