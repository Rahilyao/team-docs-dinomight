# Наш DevOps проект

## Описание проекта
Здесь общее описание...

## Команда
Ормонова Рахиля, devops
Эркинбекова Эльнура, Backend developer

## Стек технологий
Docker, Kubernetes, Linux
Python/FastAPI, PostgreSQL

## Инструкции по запуску
1. Клонируйте репозиторий и перейдите в директорию проекта:
   git clone https://github.com/Rahilyao/team-docs-dinomight.git && cd project
2. Создайте файл .env на основе шаблона .env.example и укажите необходимые переменные окружения:
   cp .env.example .env
3. Соберите и запустите контейнеры с помощью Docker Compose:
   docker compose up -d --build
main
4. Примените базы данных и миграции в локальном кластере:
   `kubectl apply -f ./k8s/`
5. Проверьте статус запущенных сервисов через командную строку:
   `kubectl get pods`
