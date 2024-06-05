# Jenkins Docker

## Summary
This sets up a Jenkins instance in Docker to allow for testing. The intent is for this project to be modular & allow for it to be incorporated into a DSO pipeline.

## Howto
- docker build .
- docker-compose up -d
- copy paswor dfrom /var/jenkins_home/secrets/initialAdminPassword
- browse to http://localhost:8080/
- select "install suggested plugins"
- wait for about 5 mintues while plugins install...
- setup admin user

## References
- https://dev.to/msrabon/step-by-step-guide-to-setting-up-jenkins-on-docker-with-docker-agent-based-builds-43j5
- https://www.jenkins.io/doc/book/installing/docker/
