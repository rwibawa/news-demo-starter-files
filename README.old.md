# News Demo starter files
learn golang

Reference:
* [web development with go](https://freshman.tech/web-development-with-go/)
* [JSON-to-Go](https://mholt.github.io/json-to-go/)

## 1. Setup
```sh
$ git clone https://github.com/Freshman-tech/news-demo-starter-files
$ cd news-demo-starter-files

$ go build
$ ./news-demo-starter-files.exe
```
Open [localhost:3000](http://localhost:3000)

## 2. Add a module
```sh
$ go get github.com/joho/godotenv
```

## 3. Automatically restarting the server
```sh
$ go install github.com/air-verse/air@latest
$ air
```