# Brooma LegalSM Project

## Структура модулей

`persistent` - Data Access Layer: содержит модели и репозитории.

`logic` - Business Logic Layer: содержит сервисы, инкапсулирующие всю бизнесс-логику.

`api` - Web API Layer: содержит web контроллеры REST API.

## Зависимости

Перед развёртыванием проекта необходимо установить:

1. Java 1.8
1. Gradle 2.10
1. Tomcat 8.0

## Сборка

Для сборки достаточно выполнить команду `gradle clean build` в корневом проекте. 
Затем артифакт `api-1.0.war` задеплоить в App Server.

Для запуска тестов введите выполните команду: gradle test