Отчёт о тестировании KeyValidator

Приложение KeyValidator распространяется в виде файла KeyValidator.class, предназначенного для работы на платформе Java 8+.
3.11.2020 г. было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 0 часов 30 мин.

В результате тестирования выявлены следующие дефекты:
* [Валидный ключ не проходит проверку](https://github.com/Dima-Melnikov/KeyValidator/issues/1#issue-786812660)
* [Невалидный ключ проходит проверку](https://github.com/Dima-Melnikov/KeyValidator/issues/2#issue-786813062)

* [Файл KeyValidator.class для скачивания](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class)

* [Файл .gitignore](https://github.com/netology-code/javaqa-homeworks/blob/master/.gitignore)

* [В качестве тестовых данных использовались данные Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

Ожидаемый результат:
* 80b427f8-92cd-3aae-ba04-3927fbe17c6: Ок
* 387eedc6-12e9-3b32-9881-63b6b5e85317: Ок
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: FAIL

Фактический результат:
* 80b427f8-92cd-3aae-ba04-3927fbe17c6: FAIL
* 387eedc6-12e9-3b32-9881-63b6b5e85317: FAIL
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: Ок

Тестирование производилось в следующем окружении:

Windows 10 Home x64
Java Version 11
