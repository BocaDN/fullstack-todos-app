# Welcome to my project!

### To clone this repository successfully you need to ensure git submodules are pulled as well:

```bash
git clone --recurse-submodules https://github.com/BocaDN/fullstack-todos-app.git
```

![git-clone-submodules](images/git-clone-submodules.png)

### The simplest way to run this application locally is by using the docker-compose.yaml file:

#### Run the following command inside a terminal with the cloned repository as the targeted directory:

```bash
docker-compose up
```

Make sure you have [docker-compose installed](https://docs.docker.com/compose/install/) on your machine before attempting to run the command. Something similar to the GIF below should appear: 

![docker-compose-up](images/docker-compose-up.GIF)

#### To access the application go to this link in your browser:

```bash
http://localhost:3000 
```

### This should be the landing page:

![NextJs-LandingPage](images/NextJs-LandingPage.png)

### The tasks menu:

![NextJs-MyTodos](images/NextJs-MyTodos.png)

### I used Jenkins for simplifying the build process. Here are some screenshots:

![Jenkins-Nextjs](images/Jenkins-Nextjs.png)
![Jenkins-Spring-Boot](images/Jenkins-Spring-Boot.png)
