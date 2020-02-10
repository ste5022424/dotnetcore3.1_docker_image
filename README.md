# dotnetcore3.1 dockerfile example

## docker build

```bash
docker build -t mydotnetcore:v1 .
```

## docker run

```bash
docker run -p 8989:80 --name mydotnetcore3.1 mydotnetcore:v1
```

## View the website at: [http://localhost:8989/](http://localhost:8989/)