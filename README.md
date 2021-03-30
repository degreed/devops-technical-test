# Degreed DevOps Technical Test

## Introduction:
Welcome to Degreed! This technical test is mainly a way for us to understand a little more about you and to give yourself and ourselves a better idea of what working together will look like. Please feel free to copy this repo to a private one of your own and invite us to it to review when you are complete, we would recommend making your changes as a PR if possible for us to review and bounce back and forth.


## Part 1.

### Fix the Docker Build
At the moment the .NET application is failing to build using the `docker-compose build` command in the app directory, please review and repair the docker-compose process, feel free to search the web for an answer.

## Part 2

### Kubernetes deployment

To a cluster you will need to deploy the application, this can be your local minikube if you like using any container registry, this application requires the application to be deployed with sqllite, the tools you use to deploy this is up to yourself, we recommend Helm if you are stuck.

Requirements:
* Kubernetes Deployment, Ingress, Service and HPA