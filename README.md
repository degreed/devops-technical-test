# Degreed DevOps Technical Test

## Introduction:
Welcome to Degreed! This technical test is mainly a way for us to understand a little more about you and to give yourself and ourselves a better idea of what working together will look like.


## Part 1.

### Fix the Docker Build
At the moment the .NET application is failing to build using the `docker-compose build` command in the app directory, please review and repair the docker-compose process, feel free to search the web for an answer.

## Part 2.

### AKS Cluster provisioning
Using any provisioner tool you would like we would like you to create a template which creates a working AKS Cluster from scratch, this should be created in a Github repository which should allow anyone to create an AKS cluster from terraform with minimal configuration. This can be a bare minimum vm sized stack, the cluster will need to have both a windows node pool and a Linux Node Pool, nothing fancy is required here.
 

## Part 3

### Kubernetes deployment

To this cluster you will need to deploy a full stack application, this application requires both a fullstack Application and a database which it communicates with in two seperate containers, the tools you use to deploy this is up to yourself, whether you write a github action or azure devops pipeline is all up to you. 

Requirements:
* Kubernetes Deployment, Ingress, Service and HPA