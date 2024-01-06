# String Reverser

Сервис с функицоналом разворота строки, с поддержкой веб-формы и RESTful API.

Выполнил студент группы МПИ-23-1-1 Коновалов Матвей
## Стек
Java 17, Spring Boot, Spring Web, Lombok, Maven

## Запуск (windows)
Для запуска приложения посредством Docker вы можете использовать следующие команды:

1. Перейдите в папку docker из корневого каталога проекта:
```
cd src/main/docker
```
2. Откройте её в терминале и выполните следующую команду:
```
docker-compose up
```
Контейнер с приложением будет доступен по адресу http://localhost:8080/

## Использование

1) Запрос: POST  `/api/dev/reverse`
```json
{
  "text": "simple text to reverse"
}
```
Ответ:
```json
{
  "result": "esrever ot txet elpmis"
}
```