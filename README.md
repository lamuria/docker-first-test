# docker-first-test
Just a node server running on docker

To run the node server on docker follow this steps:

`docker run -p 49160:8080 -d lamuria/docker-node-server`

`curl -i http://127.0.0.1:49160` should return something.

If you are having problems connecting to the container, try run `docker-machine ip default` and use the returned ip on curl
