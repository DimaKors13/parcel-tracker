## Сервис отслеживания посылок "Parcel tracker"

Данный репозиторий представляет программу, реализующую сервис отслеживания посылок.
В качестве СУБД используется SQLite.

Для проекта разработано автоматическое тестирование на базе пакета testify.
В репозитории применяется система CI, CD GitHub Actions. Согласно настройкам при каждом push`е происходит запуск тестов и в случае, если тесты завершены успешно, происходит сборка Docker образа и дальнейший push образа в Docker.Hub.

Образ доступен по имени: "dimakors13/parcel-tracker".

## Технологии
Для работы Parcel tracker были использованы следующие пакеты и технологии:
- [sqlite] - database
- [Docker] - containerization
- [GitHub Actions] - CI/CD
- [testify] - testing


   [sqlite]: <https://www.sqlite.org>
   [Docker]: <https://www.docker.com>
   [GitHub Actions]: <https://github.com/actions>
   [testify]: <https://github.com/stretchr/testify> 
   