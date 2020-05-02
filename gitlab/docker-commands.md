# Update socker
sudo docker-compose pull

# stop docker
# sudo docker compose down

# rebuild
sudo docker-compose up --force-recreate --build -d

# show logs
sudo docker logs -f gitlab_web_1

