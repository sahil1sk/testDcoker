# DOCKER COMPOSE HELPS TO RUN THE MULTI CONTAINER DIRECTLY using docker-compose file instructions 
# basic meaning is that if web app need two localhost or two server one for database and one for frontend
# then in normall docker run we will run two container separately but using docker-compose we run two container directly through docker-compose file instructions
		
			COMMANDS
# for building the docker compose use given command
docker-compose build

# for run the compose file after build use the given command
docker-compose up

# for runing dokcer in background use given command
docker-compose up -d

# for stop the compose file which is running in the backround use given command
docker-compose down

