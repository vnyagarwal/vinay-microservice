docker build -t mongodb .

docker run --name mongodb1 -d --publish-all  mongodb

docker ps

#port no in dockerfile change accordingly 

docker port mongodb1 27017(container port)

#port no on host 

echo "show dbs" | mongo localhost:49155



# to install mongo b on centos we need to to have mongodb-org.repo which will have download repo details .