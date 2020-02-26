# Go Server Example

This is a simple web server writtin in vanilla Go (no frameworks). This is basically what you get following [the tutorial on the official wiki](https://golang.org/doc/articles/wiki/). 

## Local Development

To run this locally, [make sure you have Go installed](https://golang.org/doc/install?download=go1.14.darwin-amd64.pkg) and then:

```bash
go build wiki.go
./wiki
```

You should then be able to navigate to `http://localhost:8080/view/render` and do some basic editing operations.

## Deploying on Render

You can deploy with one click by clicking this nice pretty button:

Or you can fork this repo to your github and follow these steps:

![render2](https://user-images.githubusercontent.com/6764957/75396140-d85b0e80-58c1-11ea-834d-0e6900ce25c7.gif)

1. Head to https://dashboard.render.com/web/new
2. Name it whatever you like
3. Build command: `go build wiki.go`
4. Start command: `./wiki`
5. Plans: Whatever you like
6. (Optional but Recommended) Advanced -> Add Disk -> (Whatever Name) -> Mount Path: `/data`
7. Click "Create Web Service"!

In a few minutes your site should be live on https://YOUR-SUBDOMAIN-HERE.onrender.com/view/test.