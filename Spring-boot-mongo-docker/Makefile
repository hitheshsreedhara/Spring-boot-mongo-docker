build:
	sudo docker pull mongo
	sudo docker build -t spring-boot .

run:
	sudo docker run --name mongo -d -p 27017:27017 mongo
	sudo docker run --name spring-api -d -p 8080:8080 spring-boot

inspect:
	 sudo docker network inspect spring-boot


stop:
	sudo docker stop $$(sudo docker ps -a -q)

remove:
	sudo docker rm $$(sudo docker ps -a -q)i
