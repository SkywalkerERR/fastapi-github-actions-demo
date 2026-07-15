# FastAPI GitHub Actions CI/CD Demo

## Pipeline

1. Developer pushes code
2. GitHub Actions runs tests
3. Docker image is built
4. Image is pushed to GHCR
5. Deployment stage is prepared

## Technologies

- Python
- FastAPI
- Pytest
- Docker
- GitHub Actions
- GHCR

---

## Настроил CI/CD pipeline в GitHub Actions. 
При push запускаются автоматические тесты, после успешного прохождения собирается Docker image и публикуется в GitHub Container Registry. Deployment stage реализован через отдельный job с зависимостью от успешного CI.