# Deploy a vanilla Go server

This is a simple web server writtin in vanilla Go. It is based on [the tutorial on the official wiki](https://golang.org/doc/articles/wiki/). 

No frameworks were harmed in the making of this tutorial.

## Deployment

You can deploy with one click by clicking this nice pretty button:

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

Or you can:

1. Fork [this repo](https://github.com/sw-yx/render-vanilla-go-example) on GitHub.
2. Create a new Web Service on Render, and give Render permission to access your new repo.
3. Select Go for the environment and use the following values during creation:
- Build Command: `go build wiki.go`
- Start Command: `./wiki`
- This will start the app executable compiled during build.


That’s it! Your simple Go server will be available on your `onrender.com` URL as soon as the build finishes. You can access a page on the `/view/test` subdomain, e.g. `https://YOUR-SUBDOMAIN-HERE.onrender.com/view/test`.

## Local Development

To run this locally, [make sure you have Go installed](https://golang.org/doc/install?download=go1.14.darwin-amd64.pkg) and then:

```bash
go build wiki.go
./wiki
```

You should then be able to navigate to `http://localhost:8080/view/render` and do some basic editing operations.

## Deployed Screenshots

![image](https://user-images.githubusercontent.com/6764957/75396941-b19dd780-58c3-11ea-94cc-9b4ad25a0cac.png)

![image](https://user-images.githubusercontent.com/6764957/75396956-b6fb2200-58c3-11ea-9d5d-84ebeec78970.png)
