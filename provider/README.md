To build the docker image for the node server

docker build -t myapp .

To run it and make it available on host port 3000 

docker run -p 3000:3000 myapp
