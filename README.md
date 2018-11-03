## Prereqs
docker

## How to Run
```
$ docker build -t app .
$ docker run -d -p "8080:8080" --restart always --name app app 
```
