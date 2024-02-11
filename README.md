This is a GOLang application using the CI GitHub Actions and Docker for deployment.

## Install Application

```bash
go mod tidy
```

## Getting Started

First, run the application:

```bash
go run math.go
```

## Run Tests

```bash
go test
```

## Run Docker

```bash
docker build -t goapp .
docker run --rm goapp
```