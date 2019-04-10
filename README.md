# hello-from-docker

e.g.
```
docker build -t example/hello-go:latest .
docker container run -d -p 9000:8080 --rm example/hello-go
curl http://localhost:9000
-> Hello From Docker!
```
