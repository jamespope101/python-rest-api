# CONTRIBUTING

## How to build the Dockerfile
```
docker build -t python-rest-api .
```

## How to run the Dockerfile locally

```
docker run -dp 5000:5000 -w /app -v "$(pwd):/app" python-rest-api sh -c "flask run"
```
