# Template Api

This is the Template service with fqdn go.micro.api.template.

## Getting Started

### Run Service

```
$ go run main.go
```

### Building a container

If you would like to build the docker container do the following
```
CGO_ENABLED=0 GOOS=linux go build -a -installsuffix cgo -ldflags '-w' -o template-api ./main.go
docker build -t template-api .

```
