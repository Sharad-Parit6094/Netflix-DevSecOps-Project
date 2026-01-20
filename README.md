# Netflix-DevSecOps-Project
## Deploy Netflix Clone on Cloud using Jenkins - DevSecOps Project!

### Phase 1: Initial Setup and Deployment
#### Step 1: Launch EC2 (Ubuntu 22.04):

Provision an EC2 instance on AWS with Ubuntu 22.04.
Connect to the instance using SSH.
#### Step 2: Clone the Code:
Update all the packages and then clone the code.

#### Step 3: Install Docker and Run the App Using a Container
#### Step 4: Get the API Key:
Open a web browser and navigate to TMDB (The Movie Database) website.
Click on "Login" and create an account.
Once logged in, go to your profile and select "Settings."
Click on "API" from the left-side panel.
Create a new API key by clicking "Create" and accepting the terms and conditions.
Provide the required basic details and click "Submit."
You will receive your TMDB API key.

### Phase 2: Security
Install SonarQube and Trivy:
Install SonarQube and Trivy on the EC2 instance to scan for vulnerabilities.
Integrate SonarQube and Configure:
Integrate SonarQube with your CI/CD pipeline.
Configure SonarQube to analyze code for quality and security issues.

### Phase 3: CI/CD Setup
Install Jenkins for Automation:
Install Jenkins on the EC2 instance to automate deployment: Install Java.

### Phase 4: Monitoring
Install Prometheus and Grafana:
Set up Prometheus and Grafana to monitor your application.
Installing Prometheus:
First, create a dedicated Linux user for Prometheus and download Prometheus

### Phase 5: Kubernetes
Create Kubernetes Cluster with Nodegroups

### Phase 6: Deploy Application with ArgoCD
Install ArgoCD

### Phase 7: Cleanup
Cleanup AWS EC2 Instances

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/755e7c4e-2327-4a4c-a946-155fef7d85a7" />
