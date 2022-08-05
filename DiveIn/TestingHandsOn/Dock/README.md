# Building an Image
<div style="text-align:center" markdown="1">

 ![alt text](https://imgs.search.brave.com/Ys9A3TcP_XhEgMY23e4wazTNDc9qGq6XLTrS7ysW5nw/rs:fit:1200:401:1/g:ce/aHR0cHM6Ly9idWRk/eS53b3Jrcy9ibG9n/L3RodW1ibmFpbHMv/YnVpbGQtZG9ja2Vy/LWltYWdlLWNvdmVy/LnBuZw)
 
 </div>

## Steps to follow Along:
1. Create a folder to work in : `mkdir <foldername>`
1. Create a new file : `touch <filename>` ,the filename should have extension
1. Use your IDE to write code in the file
1. save the file 
1. Incase you are unable to run it due to permission issues run : `chmod +x <filename>`
    - I am planning use javascript and node to run javascript locally.
    So all the code files will be in js 
    - To check installation version use `node -v` and `npm -v` on terminal

1. I have used `node app.js` to run my file locally on terminal.

1. Create a file named 'Dockerfile' or run command `touch Dockerfile`

## How to write a DockerFile

### Resources
- [How to write a Dockerfile (Preferred)](https://hub.qovery.com/guides/tutorial/how-to-write-a-dockerfile/)
- [How to write a dockerfile](https://www.educative.io/answers/how-do-you-write-a-dockerfile)

- [Docker build (Documentation)](https://docs.docker.com/engine/reference/commandline/build/)

You can find my Dockerfile in the 'Dock' Folder 

After writing the Dockerfile go to the terminal and in make sure you are in the correct directory.

1. Type in `docker build -t <repo/image_name>:<tag/version num> . `

1. Use `docker image ls` to list all current  docker images

1. To delete a Docker Image: `docker rmi <IMAGE_ID>`

#### *You can build from Github repo with `docker build <url of repo>` but the repo should have a dockerfile ofc 

## Running the Docker Image locally from any directory
`docker run <image_name:tag>`

### Resources:
As you have come this far you may want to explore further into the depths of Docker as a tool so here you go

***~ [Docker Documentation](https://www.docker.com/play-with-docker/) ~***
