DevOps-Muhammad-Arsalan-334
Simple static HTML served by nginx. Dockerized and ready for CI/CD to Azure App Service (Container).

Files added:
- `index.html` — app page showing "Muhammad Arsalan — NUM-BSCS-2023-34"
- `Dockerfile` — uses `nginx:alpine` to serve `index.html`
- `.github/workflows/ci-cd.yml` — GitHub Actions workflow to build, push to ACR and deploy to Web App

Quick start (local):
```
docker build -t devops-app:local .
docker run -p 8080:80 devops-app:local
# open http://localhost:8080
```

Repository name to use everywhere: `DevOps-Muhammad-Arsalan-334` (GitHub account: MuhammadArsalan16)
