# K8s
This repo contains demo to:
        1.	Containerizing this app using "dockerfile".
        2.  Creating K8s manifest file Secret, Deployment and Service to showcase the orchestration of conatiner
        
        
Containerization using Docker
A file named Dockerfile with no extenion will be created and the image will be pushed to docker hub registery

K8s manifest File
A secret is required to connect the dployment with docker hub repository to pull the image
A deployment will be created which in tern create a replica set of pods and the image will be pulled from docker registry
A service will expose the application to an external IP.
