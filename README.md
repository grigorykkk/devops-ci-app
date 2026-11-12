# devops-ci-app

Учебное Flask-приложение для практической работы №10.

Pipeline GitHub Actions: lint (Pylint) → test (pytest) → image (сборка Docker-образа, smoke-тест `/health`, публикация в GHCR).

Образ: `ghcr.io/grigorykkk/devops-ci-app` (теги: полный SHA коммита и `latest`).


