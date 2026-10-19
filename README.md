# STAge

docker build -t myimage .

docker run -d -p 5001:5001 --name MyCont myimage:latest

docker login

docker tag myimage mikeross34d/myapp:v1

docker push mikeross34d/myapp:v1

docker pull mikeross34d/myapp:v1
