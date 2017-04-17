# Concourse Setup for Rails Scaffold App

## Login
```bash
fly -t fh login --concourse-url http://192.168.1.15:8080
```

## Set Pipeline
```bash
fly set-pipeline -t fh -p scaffold-pipeline -c pipeline.yml
```
