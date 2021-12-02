# K8s
This repo contains demo to: <br />
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1.  Containerizing this app using "dockerfile". <br />
 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2.  Creating K8s manifest file Secret, Deployment and Service to showcase the orchestration of conatiner <br />
<br />       
<b>Containerization using Docker</b><br />
A file named Dockerfile with no extenion will be created and the image will be pushed to docker hub registery<br />
<br />
<b>K8s manifest File</b><br />
A secret is required to connect the dployment with docker hub repository to pull the image<br />
A deployment will be created which in tern create a replica set of pods and the image will be pulled from docker registry<br />
A service will expose the application to an external IP.<br />
