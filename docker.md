# Docker 
    Dockerfile
    .dockerignore
    volume
    bind
    ARGuments & ENVironment variable
<p> &nbsp;</p>  

## Types Docker Volumes
- /app/node_modules   -> **anonymous valume**
- *nameVolume*:/app/node_modules ->  **nameVolume**




# Files
    -> dockerignore 
    -> Dockerfile

<p>&nbsp;</p>    

# Containers & Networks
 -     Container and network request 
   -  work by default 
 -      communication between containers
   - creating Container Networks
     - docker run --network my_network_name
        - create network  just by using this command ---> docker network create network_name  
        - just put container_name in place of localhost or url
     
   - anotherway
     - inspect container 
     - Copy container Ipaddresss 
     - past the ip address in url 
 -     communication between host and container     
    -   host.docker.internal

    




    