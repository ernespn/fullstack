# loadbalancer-calculator
load balancing microservices using nginx
### Requirements
- Docker
- Docker compose

### Usage
- Clone the repo
- run "docker-compose up -d", this will create all the images that are needed F#/Python/Nginx
- run docker-compose logs to see if something went wrong
- play with the services: using curl you can check that is balancing the traffic to the different servers, example:
-- curl http://{docker-machine ip}/add/3/4
- run docker-compose stop when you are tired of playing with it
