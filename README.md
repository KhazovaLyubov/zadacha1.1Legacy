Отчёт о тестировании KeyValidator


Дата начала 12.09 - Дата окончания 12.09

Было проведено 
1. Тестирование установки приложения OpenJDK11.
1. Дымовое тестирование приложения KeyValidator

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:

https://github.com/KhazovaLyubov/zadacha1.1Legacy/issues/3#issue-700216363
https://github.com/KhazovaLyubov/zadacha1.1Legacy/issues/2#issue-700214171


В процессе тестирования использовались следующие артефакты:

1. Тест-кейс " Руководство использования KeyValidator"
1. Тест-кейс "Инструкция по установке OpenJDK11"
1. Баг Репорт #2
1. Баг Репорт №3


В качестве тестовых данных использовались данные "Руководство использования KeyValidator":

Валидные ключи:

8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
80b427f8-92cd-3aae-ba04-3927fbe17c6
b295bc63-9f03-3b4b-af80-969b39f8c262
387eedc6-12e9-3b32-9881-63b6b5e85317
c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:

18252235-78e0-44a5-8720-556f0c7da17a
e66075b6-ddad-445e-baf6-161b3289522b
b6d53250-f07e-4352-a293-6102ddf7f1ca
c2bc778a-1cb9-46c6-b435-0489649d2a42
2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Тестирование производилось в следующем окружении:

macOS Mojave Версия 10.14.6

java 11.0.8