Steps to deply node app to docker
1. sudo apt update
2. sudo apt install docker.io
3. sudo systemctl enable docker
4. sudo systemctl status docker
5. sudo apt install npm
6. sudo apt install nodejs
7. git clone https://github.com/vipulpandey1/node-todo
8. cd node-todo
9. sudo vi Dockerfile
10. sudo docker build -t vipul01/nodeapp:latest .
11. sudo docker push vipul01/nodeapp:latest
12. docker login
13. sudo docker push vipul01/nodeapp:latest
14. sudo docker pull vipul01/nodeapp:latest
15 .sudo docker run -d -p 8000:8000 --restart always vipul01/nodeapp:latest
