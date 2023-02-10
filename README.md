# Kubernetes-Training

wget https://github.com/lerndevops/code/raw/main/jdk-8u331-linux-x64.tar.gz
wget https://github.com/lerndevops/code/raw/main/apache-tomcat-9.0.63.tar.gz
wget https://github.com/lerndevops/code/raw/main/sampleapp.war
ls -l
docker pull ubuntu:18.04
docker image ls
tar -xzf jdk-8u331-linux-x64.tar.gz
ls -l
rm -r jdk1.8.0_331/
ls -l
clear
docker image ls
docker run -d -P tomcat:8.5.45
docker ps
docker image inspect tomcat:8.5.45
clear
vi sampleapdfile
ls -l
pwd
cat sampleapdfile
docker build --file sampleapp --tag sampleapp:v1
docker build --file sampleapp --tag sampleapp:v1 /tmp
docker build --file sampleapp --tag sampleapp:v1 /root

sudo hostnamectl set-hostname worker-node1
