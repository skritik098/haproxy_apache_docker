# haproxy_apache_docker

If you would like to change the Port of HAProxy Load Balancer then, in the Dockerfile of haproxy add a line - 
    EXPOSE 80
    or
In the docker-compose.yml file edit the haproxy port, baesed on the requirement.

To initiate the project execute commands as:
  docker-compose config  --> To check the status of the Final compose file   

To initialise it run command:  --> docker-compose up
