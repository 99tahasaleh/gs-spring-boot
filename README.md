# gs-spring-boot

we used the https://github.com/spring-guides/gs-spring-boot.git reository to dockerize a spring boot application with multi-stage build. 


## Run Locally

Clone the project

```bash
  git clone https://github.com/mohamadassi173/gs-docker
```

Go to the project directory

```bash
  cd gs-docker
```

Build

```bash
  docker build -t gs-boot .
```

Run

```bash
  docker run -d -p 8080:8080 gs-boot
```


## DockerHub

Run the image from DockerHub

```bash
  docker pull salehtaha/gs-boot:latest
  docker run -d -p 8080:8080 salehtaha/gs-boot:latest
```
![image](https://user-images.githubusercontent.com/57872327/177011593-f25936dd-ea31-469a-90ae-7de7cfa078d6.png)



