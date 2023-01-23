# Hadoop_Installations

<h3>Downlaod cloudera</h3>
https://drive.google.com/file/d/1WzYxDmaRnJUpAGhZcdl8WXlyc6NClDUe/view?usp=sharing

<h3>Download VM</h3>

https://www.virtualbox.org/wiki/Downloads


<h3>Putty Downlaod</h3>

https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html


<h3>File Zilla dowonload</h3>

https://filezilla-project.org/download.php?platform=win64

<h2>FOR MAC </h2>

Hi, for mac m1, try to go with below lsited steps.
Go on to your terminal                  
1. docker ps - To list running docker containers
2. docker pull cloudera/quickstart:latest - To pull docker image from repository
3. docker run --hostname=quickstart.cloudera --privileged=true -t -i -v ~/Documents/dockersrc:/Src --publish-all=true -p 8888 cloudera/quickstart /usr/bin/docker-quickstart - To start cloudera docker container



https://medium.com/@rakeshgopidi/installing-cloudera-quickstart-vm-through-docker-hub-on-mac-m1-879f4a3d0fd4
