# study-docker-dotnet-core
Study case of build app using .Net Core + Docker

## Steps

- Run Project Without Docker

```sh
dotnet run --project app
```


## Solutions

- When show the error **warning: CRLF will be replaced by LF in ...**

```sh
git config core.autocrlf true
```
