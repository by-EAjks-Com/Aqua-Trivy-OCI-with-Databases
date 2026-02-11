# Trivy Offline

Container images to develop Go applications.

```powershell
docker build --file ./Dockerfile --tag trivy-offline:latest .
docker run --rm trivy-offline:latest image alpine:3.19
```
