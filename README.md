This is a simple activity to create a Dockerfile for a simple html webpage.

The description of the work is as follows:
I created a html file of the webpage.
I then created a Dockerfile in the same directory 
The Dockerfile contains two commands: FROM and COPY
I used docker build -t shecodes-webserver-image:v1 . to build the image
I used docker run -d -p 3400:80 shecodes-webserver-image:v1 to run a container from the image

The webpage is obtained by using ocalhost:3400 on the browser. The results are shown in the webpage.PNG file.
