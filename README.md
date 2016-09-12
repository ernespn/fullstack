# loadbalancer-calculator
load balancing microservices using nginx
### Requirements
- Docker
- Docker compose

### Usage
- Clone the repo
- run "docker-compose -f docker-compose.dev.yml up -d", this will create all the images that are needed F#/Python/Nginx
- run docker-compose logs to see if something went wrong
- play with the services: using curl you can check that is balancing the traffic to the different servers, example:
-- curl http://{docker-machine ip}:8080/add/3/4
- Or check my website
-- curl http://{docker-machine ip}/
- run docker-compose stop when you are tired of playing with it
