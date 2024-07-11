# Jenkins-CI/Argo-CD pipeline to kubernetes deployment

In the Project i have implemented java application through Jenkins CI/CD pipeline 

When the Application is pushed to Github repository you can manually trigger the CI pipeline with the help of Jenkins and it will run every stage given in the pipeline this also includes scanning of image using sonarqube

after every test stage has run sucessfully the docker image is been created and pushed to docker hub and version tag is updated in manifest.yml file for k8s deployment

Argo CD is used for deployment through manifest.yml files to the kubernetes cluster

[Installation](https://hashnode.abhijeetbhovar.com/jenkins-ciargo-cd-pipeline-to-kubernetes-deployment)
