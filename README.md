#blog
academic template with hugo

docker build -t rsacal:hugo .
docker run -d --name rsacal -p 80:80 rsacal:hugo
docker-compose up -d