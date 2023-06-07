**Юнит-тесты для Stellar.Burgers. Учебный проект**

Покрытие юнит-тестами сервиса заказа бургеров [Stellar.Burgers](https://stellarburgers.nomoreparties.site/). 

- Тестами покрыты классы Bun, Burger, Ingredient и Ingredient Type.
- В maven подключены библиотеки: JUnit 4, Jacoco, Mockito. Настроен на работу с Java 11.

Команды:
- для запуска тестовых сценариев: mvn clean test
- для формирования отчёта Jacoco: mvn verify.
- для просмотра отчёта - найти файл target/site/jacoco/index.html, открыть файл в браузере.