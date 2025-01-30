# MusicNotes
MusicNotes - это система для упрощенной работы с нотными листами: загрузка, преобразование в аудиодорожки и управление через личный кабинет.

## Возможности
- Загрузка нотных листов из личного кабинета
- Преобразование в аудиоформат
- Возможность сохранения и удаления файлов из личного кабинета

## Использование
Приложение доступно по ссылке

## Установка
Для локального развертывания проекта вам понадобятся:
- Docker
- Docker Compose

### Шаги установки
1. Склонируйте репозиторий на ваше устройство:
```shell
git clone https://github.com/resdt/MusicNotes.git
cd MusicNotes
```

2. Выполните команду для сборки и запуска системы:
```shell
docker compose up --build
```

## Запуск
После того, как система будет развернута, приложение станет доступно по ссылке http://localhost:8501

## Остановка
Чтобы остановить приложение, выполните:
```shell
docker compose down
```
