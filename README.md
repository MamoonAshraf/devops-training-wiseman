#Agile vs DevOps
In Agile application development is done in sprints instead of waterfall model, with smaller teams
DevOps approach ennsure that code and infrastructure are always in a deployable state
#Define CI,Contineous Delivery and Contineous Deployment
Contineous Integration ensure that every check-in is build automatically and notify dev team incase build fails so application code is in deployable state
Contineous Delivery required manual steps before deploying to production environment or any other stage
Contineous Deployment every succesfull build is deployed to production environment directly it doesn,t involve manual approval

#What are the benefits of Cloud Computing
on-demand computing resources
Don,t have to buy resources
Elastic resources scale up or down quickly and easily to meet demand
pay for what you use only
self service -All the IT resources you need with sel-service access

#Difference b/w Git & Github
Git is a version control system that lets you manage and keep track of your source code history.
GitHub is a cloud-based hosting service that lets you manage Git repositories

#Stages of Git
working directory,staging area, remote repository

#Explain Docker Containers vs VM,s
 containers share host OS kernel,containers doesn,t pre-occupied host OS resources they they take resources as they need,containers do OS level virtuliazation.
 VM does hardware level virtualization,every VM has their own OS and resources are pre-allocated VM so they are reserved for the VM whether they use or not

# Explain Docker Architecture 
  Docker is installed on top of host OS like ubuntu,windows,Centos and containers run as processes and share hardware and Host OS kernel 

# Write command to create an nginx container in detached mode with name assignment-2 running on host port 9090 on a custom network named assignment-2

docker network create assignment-2

docker container run -d --publish 9090:80 --net assignment-2 --name assignment-2 nginx

# command to see container assignment-2 logs
docker container logs assignment-2



