This is the repository for auto deployment of our company blog/planet using writefreely as the base image and deployed on ECS. Other option is to use Ghost on Oracle cloud which would be cheaper with their lifetime free plan. Or use github


Steps:
* [ ] Create Docker image for Write freely and Nginx
* [ ] Setup database on RDS
* [ ] Write terraform file to create the ECS, publish the docker images on ECR and launch the containers
* [ ] Write CI/CD pipeline script for the same


Create docker image and upload on aws ecr
test the image locally
launch a cluster using the docker image for writefreely web image (from docker hub or aws ecr)




infra:
* ECS
* EC2
* VPS