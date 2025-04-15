FROM jenkins/jenkins:lts

USER root

# Installer Docker dans le conteneur
RUN apt-get update && \
    apt-get install -y docker.io && \
    usermod -aG docker jenkins

USER jenkins
