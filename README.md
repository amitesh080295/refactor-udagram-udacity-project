# refactor-udagram-udacity-project

Udacity - Refactor Udagram Project

## Steps Performed

- udacity-c3-restapi divided into udacity-c3-restapi-user and udacity-c3-restapi-feed
- Dockerfiles are added to all the three applications - frontend and the two backend services
- docker-compose was used to build and push the images to docker hub via build through Travis CI
- Applications were deployed to an EKS Cluster with 10 nodes using kubectl
- Screenshots for docker hub images, travis build are attached
- Additionally, screenshots for get nodes, get deployment and get services along with port forwarding and localhost udagram are attached
