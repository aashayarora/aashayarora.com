create:
	- docker stop $(docker ps -a | grep 'httpd-foreground' | awk '{print $1;}')
	- docker rmi website
	- docker-compose up
