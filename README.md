# msina-hello-world

Start with: https://start.spring.io/
Just choose web as dependency.

For docker use the spotify plugin: https://github.com/spotify/docker-maven-plugin

mvn clean package (You need to run this before docker commmand, otherwise jar file is not found)
mvn docker:build

docker run -it -p  80:8080 rameshch/helloworld

You can test by accessing the url: http://localhost/hello/ OR http://localhost/hello/Ramesh/Ch 

