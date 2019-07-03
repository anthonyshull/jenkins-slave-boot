# Jenkins Slave Boot

A Jenkins slave agent based on [evarga/jenkins-slave][evarga/jenkins-slave] and including Clojure and [Boot][boot].

## Usage

Install the Jenkins [docker-plugin][docker-plugin.]

Create a Docker Agent template and set the Docker Image to `anthonyshull/jenkins-slave-boot`.

You know have access to Boot in your builds.

## License
<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher" href="https://github.com/anthonyshull/jenkins-slave-boot">
    <span property="dct:title">Anthony Shull</span></a>has waived all copyright and related or neighboring rights to <span property="dct:title">Jenkins Slave Boot</span>.
  This work is published from: <span property="vcard:Country" datatype="dct:ISO3166"content="US" about="https://github.com/anthonyshull/jenkins-slave-boot">United States</span>.
</p>

[boot]: https://github.com/boot-clj 
[docker-plugin]: https://wiki.jenkins.io/display/JENKINS/Docker+Plugin
[evarga/jenkins-slave]: https://hub.docker.com/r/evarga/jenkins-slave
