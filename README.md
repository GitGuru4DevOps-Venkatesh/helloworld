Welcome to DevOps Central Hub!!!(WAR-style) ###
==============================================

This is the simplest possible Java webapp for testing servlet container deployments.  It should work on any container and requires no other dependencies or configuration.

docker-tomcat-satylearning
A basic tutorial on running a web app on Tomcat using Docker - SATYLearning - Subscribe my youtube channel

     https://github.com/efsavage/hello-world-war

########### Steps ###################
* Install [Docker](https://docs.docker.com/install/).
* Clone this repository - $git clone https://github.com/GitGuru4DevOps-Venkatesh/helloworld-project-1/
* cd helloworld # from your root directory
* mvn clean install # Build using maven command
* $docker build -t helloworld .
* $docker run -p 8082:8080 helloworld
* http://localhost:8082/hello-world-war-1.0.0

