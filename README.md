# Jenkins Slave Boot

A Jenkins slave agent based on [evarga/jenkins-slave][evarga/jenkins-slave] and including Clojure and [Boot][boot].

## Usage

Install the Jenkins [docker-plugin][docker-plugin.]

Create a Docker Agent template and set the Docker Image to `anthonyshull/jenkins-slave-boot`.

You know have access to Boot in your builds.

## License
![alt text][public-domain] To the extent possible under law, Anthony Shull has waived all copyright and related or neighboring rights to Jenkins Slave Boot.

This work is published from: United States.

[boot]: https://github.com/boot-clj 
[docker-plugin]: https://wiki.jenkins.io/display/JENKINS/Docker+Plugin
[evarga/jenkins-slave]: https://hub.docker.com/r/evarga/jenkins-slave
[public-domain]: http://i.creativecommons.org/p/zero/1.0/88x31.png
