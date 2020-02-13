# study-docker-dotnet-core
Study case of build app using .Net Core + Docker

## Steps

### Execute project

- Run Counter Project Without Docker

```sh
dotnet run --project app
```

or with time limit.

```sh
dotnet run --project app -- 5
```

### Publish Release

```sh
dotnet publish -c Release app
```

### Build Docker image

```sh
docker build -t myimage -f Dockerfile .
```

### Create Docker container

```sh
docker create myimage --name docker_dotnet_core
```

### Start Docker container

```sh
docker start
```

### Show created containers

```sh
docker ps -a
```

## Solutions

- When show the error **warning: CRLF will be replaced by LF in ...**

```sh
git config core.autocrlf true
```
