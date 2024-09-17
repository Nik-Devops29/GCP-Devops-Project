# Under this Project, A containerized Python/Flask application is deployed using various GCP services, ensuring scalability and streamlined resource management.
• Created and optimized a Dockerfile for the application, enabling standardized containerization for consistent deployments across different environments.
• Integrated GitHub with Google Cloud Build to automate Docker image creation and deployment to Artifact Registry, employing Git branches for feature development and testing, with merges into the main branch controlled and validated through the CI/CD pipeline.
• Orchestrated the deployment of containers to Google Kubernetes Engine (GKE) using a Cloudbuild.yaml.
• Configured separate environments—dev and prod—with distinct deployment triggers, enabling seamless and controlled deployment of applications based on the environment. file, automating the deployment process within the Kubernetes cluster.
