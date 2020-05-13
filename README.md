# Is Go outyet?

Using Docker and Go's example program called ```outyet``` to start a server that reports if a certain version of Go is out yet.

## Get started
```
git clone https://github.com/nikimanoledaki/is-go-outyet.git
cd is-go-outyet
docker run -p 6060:8080 niki2401/outyet:latest
```

Then, open `localhost:6060` in your web browser.

To exit the program, press the `control` + `C` keys.

## Run the tests
```
go test
```