# Go Server Example

This is a simple web server writtin in vanilla Go (no frameworks). This is basically what you get following [the tutorial on the official wiki](https://golang.org/doc/articles/wiki/). 

To run this, [make sure you have Go installed](https://golang.org/doc/install?download=go1.14.darwin-amd64.pkg) and then:

```bash
go build wiki.go
./wiki
```

You should then be able to navigate to `http://localhost:8080/view/render` and do some basic editing operations.