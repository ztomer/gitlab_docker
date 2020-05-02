# Update docker, rebuild and restart
sudo docker-compose pull
sudo docker-compose up --force-recreate --build -d

# stop docker
sudo docker-compose down

# Start
sudo docker-compose up

# Show logs
sudo docker logs -f gitlab_web_1

