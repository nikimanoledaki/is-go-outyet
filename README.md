# Is Go outyet?

Using Docker and Go's example program called ```outyet``` to start a server that reports if a certain version of Go is out yet.

## Get started
```
go build -t outyet .
docker run --publish 6060:8080 --name test --rm outyet
```

Then, open ```localhost:6060``` in your web browser.

To exit the program, run ```docker stop test``` from another terminal.

## Run the tests
```
go test
```