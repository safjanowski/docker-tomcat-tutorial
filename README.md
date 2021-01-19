# docker-tomcat-tutorial
A basic tutorial on running a web app on Tomcat using Docker

# Steps
* Install [Docker](https://docs.docker.com/install/).
* Clone this repository - `git clone https://github.com/softwareyoga/docker-tomcat-tutorial.git`
* `cd 'docker-tomcat-tutorial'`
* `docker build -t mywebapp .`
* `docker run -p 8080:8080 mywebapp`
* open http://localhost:8080/sample

# Links
[Sample Tomcat web app](https://tomcat.apache.org/tomcat-8.0-doc/appdev/sample/)
