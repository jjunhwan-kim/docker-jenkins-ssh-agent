FROM jenkins/jenkins:2.401.3-lts-jdk11

COPY ./ssh/* /var/jenkins_home/ssh/
COPY executors.groovy /usr/share/jenkins/ref/init.groovy.d/executors.groovy
