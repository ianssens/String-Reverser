# String Reverser

Сервис с функицоналом разворота строки, с поддержкой веб-формы и RESTful API.

Выполнил студент группы МПИ-23-1-1 Коновалов Матвей
## Стек
Java 17, Spring Boot, Spring Web, Lombok, Maven

## Запуск (windows)
Для запуска приложения вы можете использовать следующие команды:

1. Разархивируйте архив с исходным кодом, и перейдите в разархивированную папку:
```
cd moretech-backend
```
2. Откройте терминал и выполните следующую команду:
```
mvn clean package
```
Maven соберет проект и создаст jar-файл в каталоге target.

3. Запустите приложение командой:
```
java -jar target/<название_jar-файла>.jar
```
Где <название_jar-файла> - это имя jar-файла, созданного в предыдущем шаге. <br>
Приложение будет доступно по адресу http://localhost:8080

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