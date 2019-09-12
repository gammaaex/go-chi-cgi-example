# go-cgi-example

## Usage
1. `cd docker`
1. `docker-compose build`
1. `docker-compose up -d`
1. Access to `localhost:8080`
1. `docker-compose down`

## Self Build
1. Edit `main.go`
1. `cd docker`
1. `docker-compose build`
1. `docker-compose up -d`
1. `docker-compose exec go bash`
1. `go build -ldflags '-s -w' -o public/main.cgi main.go`
1. `exit`
1. `docker-compose down`
