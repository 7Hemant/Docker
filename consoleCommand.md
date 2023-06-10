-     docker build -t feedback-node:dev --build-arg DEFAULT_PORT =8080
-     docker run --name Name -d --rm -p 3000:3000   Container_name 

- docker container prune  -> remove all the container 

## Containers & Networks
-     host.docker.internal
- docker run -d --name mongobd --network Network_name Container_name

## postgres
- docker run --name some-postgres -e POSTGRES_PASSWORD=mysecretpassword -d postgres

