# php-testtask
Test task for php-developer

## Спроектировать сервис todo-list

Существует 2 сущности пользователей: родитель и ребенок. Родитель может ежедневно назначать определенные задания ребенку, по мере выполнения которых он может начислять награду в виде звездочек. Необходимо спроектировать сервис, который будет иметь следующий базовый функционал:

  - Регистрация пользователя
  - Привязка ребенка к родителю
  - Назначение родителем задания для ребенка
  - Выполнение задания ребенком
  - Подтверждение выполненного задания родителем

Требования к сервису:
  - Сервис должен запускаться в контейнеризированной(docker) среде независимо от окружения, где будет запускаться сервис
  - Структура базы данных и наполнение должно быть реализовано через миграции
  - Присутствует инструкция по запуску сервиса и по его использованию
