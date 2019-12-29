# Docker_CentOS-7_Spring-Boot
This repository holds all files needed to create a Docker container based on [CentOS 7](https://www.centos.org/), that can run a [Spring Boot](https://spring.io/projects/spring-boot) JAR using [Amazon Corretto](https://aws.amazon.com/corretto/) 11; as a privileged or non-privileged user.

The project assumes Docker is properly configured/installed on the user's system, with "$ docker -v" functioning properly from the command line.

Useful commands are shown in the comments section at the top of each "./Dockerfile".

These files show how to create a Docker container with:
* CentOS 7.
* All updates/upgrades installed.
* Amazon Corretto and simple Spring Boot based [time-retrieval web service](https://github.com/samueltoepke/Time_Web-Service) installed as a JAR file.
* New, non-privileged user added (optional).
