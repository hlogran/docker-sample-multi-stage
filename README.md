# docker-sample-multi-stage
Docker multi-stage feature sample

In this example we explore the multi-stage feature of docker, which allows us to build several docker images from an unique Dockerfile.
The commands for each image are described down bellow:

 #Prod image
 docker build -t sample-multi-stage:prod --target=prod .
 
 #Dev image
 docker build -t sample-multi-stage:dev --target=dev .
 
 #Test image
 docker build -t sample-multi-stage:test --target=test .
