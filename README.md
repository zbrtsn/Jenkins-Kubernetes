# Jenkins-Kubernetes

Jetkins --> pipeline --> docker --> dockerhub --> kubernetes

I will pull a simple Flask project from GitLab or GitHub via Jenkins. Then, I will build the project with Docker (the project includes a Dockerfile!), and push the built image to Docker Hub. Locally, I use the "kind" tool for Kubernetes. I will also activate my manifest files, i.e., .yaml files associated with the Docker Hub repository of the pushed project, through Jenkins in the same way. My goal is to automate all these processes.


## Related Projects

Here are some related projects;

[Basic Flask Project](https://github.com/zbrtsn/basic-to-do-flask.git)

  
