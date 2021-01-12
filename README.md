This is a simple activity to create a Dockerfile for a simple html webpage.

The description of the work is as follows:
I created a html file of the webpage.
I then created a Dockerfile in the same directory 
The Dockerfile contains two commands: FROM and COPY
I used docker build -t shecodes-webserver-image:v1 . to build the image
I used docker run -d -p 3400:80 shecodes-webserver-image:v1 to run a container from the image

The webpage is obtained by using ocalhost:3400 on the browser. The results are shown in the webpage.PNG file.
When the index.html file is modified, the port used is 3600 instead of 3400 and the resulting webpage is conrained in webpage2.PNG

The final Docker image can be found here: https://hub.docker.com/repository/docker/modero/shecodes-webserver-image

