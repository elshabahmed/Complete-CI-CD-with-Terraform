### This project demonstrates the implementation of a CI/CD pipeline using Terraform and Docker. It involves building an application, containerizing it into a Docker image, pushing the image to Docker Hub, provisioning AWS resources using Terraform, and deploying the application on the created resources. The project aims to automate the software development and deployment process, enabling faster and more efficient delivery of applications.

The main steps involved in the project are as follows:
### -	Building the application: The project involves building java application.

### -	Containerizing the application into a Docker image and building the Dockerfile: The application is containerized using Docker, which allows for packaging the application and its dependencies into a portable and isolated container then build the application.

### -	Pushing the image into Docker Hub

### -	Running Terraform file to create resources on AWS

### -	SSH into the instance created by Terraform and run the Docker container: Once the resources are created, the project involves SSHing into the instance created by Terraform and running the Docker container using the previously built Docker image.

