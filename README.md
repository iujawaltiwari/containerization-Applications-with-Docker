# Docker Basics



# Docker Advanced

1. Concept of images - push/pull on dockerhub

Step1:- Go to dockerhub and create account. 

Step2:- Check Docker Images.

```
docker images
```
Note => You need to know you can push only docker images on dockerHub

Step3:- Login DockerHub on local or remote machine.

```
docker login
```

```
Put Your Docker Hub Username 
Put Your Docker Hub Password 
```

Step4:- tag your image with your docker hub username.

```
docker tag <old_image_tag> <username/image>
```

Example:- 

```
docker tag flask-app:latest iujawaltiwari/flask-app
```

Step5:- Push your images in docker Hub.

```
docker push iujawaltiwari/flask-app
```

2. Docker Volumes

3. Docker Networks

4. Multi Tier Application with a database 

5. Multi Stage Docker Build ( 1GB ---> 200 MB) Comprased

6. Docker init / Docker Scout ( DevSecOps )

&. Docker Compose
