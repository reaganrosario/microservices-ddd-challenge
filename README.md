# Monolithic application to a containerized microservices challenge 

## Description
Deploy a monolithic application that is deployed directly onto instances with no containerization or orchestration, to a containerized microservices architecture orchestrated using Amazon EC2 Container Service. 

## Solution Hints

<details>
<summary>Click to expand!</summary>


https://github.com/aws-samples/amazon-ecs-java-microservices

</details>

## Base Source code
https://github.com/spring-projects/spring-petclinic

## Tags
#microservices #ecs #springframework #java #cicd

## Rubric
* All project code is stored in a github repo, you can create a git repo by forking this repo and add your changes to it.
* Use image repository to store your docker images
* The project takes a Dockerfile and creates a container in the pipeline
* Split the monolith in multiple target microservices.
* Use load balaancer to deploy the application to multiple target groups
* Deploy the ECS cluster using cloudformation
* The project performs the correct steps to do a blue/green or a rolling deployment
* Container is shipped to a staging environment where its runtime behavior can be checked using load tests
* Optional: Perform security scanning of docker containers in the pipeline
* Optional: Perform post deployment testing of your application through the pipeline.

# Suggested trainings/lsbs
* https://ecs.immersion.ecs.aws.dev/
* https://ecsworkshop.com/
* https://github.com/aws-samples/amazon-ecs-mythicalmysfits-workshop



