# Avito PaaS 

PaaS — это платформа для разработки и эксплуатации сервисов. Основная цель платформы — позволить разработчикам тратить время на реализацию бизнес-логики, а не возню с инфраструктурой и интеграциями.

Для работы с платформой мы предоставляем консольную утилиту Avito и PaaS-дашборд как основные высокоуровневые интерфейсы. Через них проходит весь жизненный цикл разработки микросервисов.

## Зачем платформа нужна разработчикам?

PaaS покрывает весь жизненный цикл разработки:

- В ней есть все необходимые инструменты для решения повседневных задач:
  - автоматическая интеграция с базами данных;
  - структурированное логирование и метрики;
  - работа с секретами;
  - очереди задач;
  - шина данных;
  - live reload для локальной разработки;
  - инструменты для запуска тестов.
- Не нужно писать сложные конфигурации прокси для баз данных и других хранилищ.
- Не нужно вручную писать клиентов для сервисов.
- Не нужно поддерживать большие и сложные Helm-конфигурации.

## Зачем платформа нужна Авито?

- Повышение скорости разработки всего Авито (ТТМ).
- Внедрение новых инфраструктурных фич и проверки качества сразу на всю компанию.
- Обновление версий инфраструктурных компонентов без необходимости привлечения разработчиков.
- Актуальность технического стека и используемых инженерных практик.
- Стабильность системы: снижение MTTU поиска причин деградаций.
- Улучшение эффективности потребления ресурсов

## Что почитать и посмотреть про Avito PaaS?

[Платформа как сервис в Авито: как это устроено](https://habr.com/ru/company/avito/blog/527400/)

[Avito PaaS meetup #1](https://www.youtube.com/playlist?list=PLknJ4Vr6efQH_DQnNP8fe5iNoU3wTdeAa)