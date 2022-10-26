[![Build Status](https://travis-ci.org/VadimShein/job4j_echoserver.svg?branch=master)](https://travis-ci.org/VadimShein/job4j_echoserver)

# <p align="center">Простой веб сервер</p>

## Используемые технологии:
* Java 11

## Описание:
Простой веб серевер, который приветствует пользователи при отправке команды Hello 
и завершает работу при отправке команды Bye.

## Использование
1. Отпрвка сообщения, сервер возвращает ответ
```
http://localhost:9000/?msg=Hello
```

2. Завершение работы
```
http://localhost:9000/?msg=Bye
```

## Запуск проекта:
1. Скопировать проект 
```
git clone https://github.com/VadimShein/job4j_echoserver
```

2. Выполнить сборку проекта 
```
mvn clean package -DskipTests
```

3. Запустить проект
```
java -jar target/job4j_echoserver-1.0.jar
```

## Контакты:
[![alt-text](https://img.shields.io/badge/-telegram-grey?style=flat&logo=telegram&logoColor=white)](https://t.me/SheinVadim)
[![alt-text](https://img.shields.io/badge/@%20email-005FED?style=flat&logo=mail&logoColor=white)](mailto:shein.v94@mail.ru)
