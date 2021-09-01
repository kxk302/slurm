Credit for docker-compose file goes to Rodrigo Ancavil (https://medium.com/analytics-vidhya/slurm-cluster-with-docker-9f242deee601)

To start a Slurm cluster:
> docker-compose build\
> docker-compose up -d

To stop the Slurm cluster:
> docker-compose down

To view the container logs:
> sudo docker logs containerName

To SSH into the container:
> sudo docker exec -it containerName /bin/bash
