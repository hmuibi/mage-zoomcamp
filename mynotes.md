Copy environment credentials 
cp dev.env .env

docker compose build

docker pull mageai/mageai:latest

docker compose up