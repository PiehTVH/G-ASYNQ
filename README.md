# G-ASYNQ

## Prerequisites

Make sure redis already exists:

```console
docker-compose up -d
```

## Quick start

1. Install dependencies

```console
go mod download
```

2. Start worker

```console
go run worker/main.go
```

3. Start dashboard

```console
go run dashboard/main.go
```

4. Start app-server

```console
go run app/server.go
```
