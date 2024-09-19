# Multi-Container-Application-Deployment-with-Docker-Compose-and-Kubernetes
This project demonstrates the deployment of a multi-container application using Docker Compose and Kubernetes. The application consists of a frontend, backend, and database.
Project Repositories

Backend: https://github.com/Anand-1432/Techdome-backend
Frontend: https://github.com/Anand-1432/Techdome-frontend

Application Architecture
![Techdome drawio](https://github.com/user-attachments/assets/e8aea3c8-5ca3-4e87-93b6-7c6f91f04819)

Tools Used

Docker
Docker Compose
Minikube
Kubernetes

### Deployment Strategy
Our deployment strategy involves two stages:
Local Development: Using Docker Compose
Allows for easy setup and testing of the entire application stack
Simplifies environment consistency across development machines

Production-like Environment: Using Kubernetes
Provides scalability and robustness for production workloads
Allows for easy management of multiple containers and services

### Building and Deploying the Application
Using Docker Compose
![image](https://github.com/user-attachments/assets/eb617f9a-122d-4b04-a5a5-7fe0c89ee65e)

Using Kubernetes
![image](https://github.com/user-attachments/assets/c6f28495-92ad-4d26-923a-134165ae0410)

Application Functionality
![image](https://github.com/user-attachments/assets/41ab5ece-480e-47d7-862c-454fed49819a)

Screenshots
![image](https://github.com/user-attachments/assets/3dbe6e1d-cbca-42ba-8f63-54db903eecdc)

![Screenshot 2024-09-19 010554](https://github.com/user-attachments/assets/fb6d345c-11ab-4453-8b04-5b855081e86b)

Frontend results
![image](https://github.com/user-attachments/assets/ad50a594-3654-4d3e-b237-1b03398cc7b3)



### Bonus Features
Bonus Features
Infrastructure Scaling: Implemented Horizontal Pod Autoscaler (HPA) for the backend, scaling the replicas based on CPU utilization. If CPU usage exceeds 80%, additional backend replicas are automatically created to handle increased load.

Rollback Strategy: Established a rollback strategy for infrastructure changes by maintaining version control of Kubernetes deployments, allowing easy reversion to a previous state if necessary.




### Documentation
For more detailed information about the application architecture, deployment strategy, and management instructions, please refer to the Documentation.
### Demonstration
[Include a link to your recording or additional screenshots demonstrating the application's functionality and deployment approach]
