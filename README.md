# Adminer with support Oracle database
This is an Adminer image that also supports the Oracle database

## Build 

You can build image with the below command

```bash
docker build -t mdehnavi/adminer-oracle:4.7.6 .
```

## How to use

### Local run

You can run locally with the below command

```bash
docker run --rm -it -p 8080:8080 mdehnavi/adminer-oracle:4.7.6
```

In your browser, you can access it with `localhost:8080`

### Run in Kubernetes

You can use it in Kubernetes by applying `adminer-oracle.yaml` with the below command

```bash
kubectl apply -f adminer-oracle.yaml
```

