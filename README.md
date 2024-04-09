# CI-CD-Voting-App
Automating the deployment and continuous integration of a voting application, ensuring seamless updates and efficient testing through CI/CD pipelines. Streamlining the development process from code changes to production deployment for a responsive voting experience.

![CICDDiagram (1)](https://github.com/bnb-22/CI-CD-Voting-App/assets/122742199/497f3881-0d27-4f57-84a3-94e5283c21b2)


Project Name: Voting App

Description:

The Voting App project is a containerized application that allows users to vote for their preferred choices among a set of options. It consists of several microservices that handle different aspects of the voting process. The project utilizes Docker for containerization and Azure DevOps Pipelines for building, pushing, and updating Docker images in Azure Container Registry. 

Microservices:

1. Vote Service: Allows users to vote for their preferred choices.
2. Worker Service: Handles background tasks or processing related to the voting app.
3. Result Service: Displays the results of the voting process.

Technologies Used:

- Docker: Containerization platform used to package the application and its dependencies into containers.
- Azure DevOps Pipelines: CI/CD tool used for automating the build, test, and deployment process.
- Azure Container Registry: Hosts Docker images for the project.
- Kubernetes: Container orchestration platform for deploying, managing, and scaling containerized applications.

Source Repository:

The application source code can be cloned from the [dockersamples/example-voting-app](https://github.com/dockersamples/example-voting-app.git) GitHub repository.

![image](https://github.com/bnb-22/CI-CD-Voting-App/assets/122742199/8e376e97-df2f-42e8-92d3-8ca9f4883c64)


How to Use:

1. Clone the repository from [dockersamples/example-voting-app](https://github.com/dockersamples/example-voting-app.git) to your Azure Devops Repository.
2. Make necessary changes to the Kubernetes manifest files if required.
3. Build Docker images for each microservice using Azure DevOps Pipelines.
4. Push the Docker images to Azure Container Registry.
5. Deploy the application to Kubernetes cluster using the updated Kubernetes manifest files.

Additional Notes:

- Ensure proper configuration of Azure DevOps Pipelines and Azure Container Registry for seamless CI/CD workflow.
- Use Kubernetes for efficient management of containers in production environment.
- Customize and extend the application as per specific requirements or use cases.

Contributing:

Contributions to the project are welcome! Feel free to fork the repository, make changes, and submit pull requests.
