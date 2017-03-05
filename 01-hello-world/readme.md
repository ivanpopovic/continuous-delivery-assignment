# CONTINUOUS DELIVERY - 01-hello-world


## 1. Build image

```shell
docker build -t popovic/hello-world .
```


## 2. Run image

```shell
docker run -p 4001:8080 -d popovic/hello-world
```

## 3. Test the app

```shell
curl -i localhost:4001
```
