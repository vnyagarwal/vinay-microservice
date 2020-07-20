# create volume of docker machine 
docker volume creare --name config
docker volume creare --name data
docker volume creare --name log

build Dockerfile 
docker build -t mqtt1 .

RUN 
docker run --name testmqtt1 -p 1883:1883 -v config:/mqtt/config -v data:/mqtt/data -v log:/mqtt/log mqtt1

Ooutput : 
It will tun config file and open up the ports and can see version . 
to test we need mqtt application 