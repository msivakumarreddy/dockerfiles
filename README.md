### Dockerfile
Dockerfile is the declarative way of creating our own images. we need to use docker build command to build the images.

```
docker build -t [repo-URL]/[username]/[image-name]:[version] .
```
We should run above command where Dockerfile exists.

We need to use below command to push image to Dockerhub.

```
docker push [repo-URL]/[username]/[image-name]:[version]
```