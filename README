# Building docker image

	docker build -t mirza/debian .


# Running the debian docker container

	# Clean-up old instance
	docker stop mirzadebian
	docker kill mirzadebian
	docker rm mirzadebian

	# start container
	docker run --name="mirzadebian" -it -rm -v /home/mirza/project:/home/mirza/project -v /home/mirza/.ssh/:/home/mirza/.ssh mirza/debian

