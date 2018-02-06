# Docker_Jenkins
This is repository which is used to test using Docker and Jenkins together



#Command

docker run -u root --rm -p 8080:8080 --name jenkins -v /home/kist/Docker_example/new_jenkins:/var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock subicura/jenkins:2
