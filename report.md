# Отчёт о тестировании приложения KeyValidator

## Краткое описание

03.11.2020 было проведено тестирование установки ПО OpenJDK, а также функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 60 минут.

В результате тестирования установки OpenJDK дефектов не выявлено.
В результате функционального тестирования KeyValidator выявлены следующие дефекты:
1. [Приложение KeyValidator выдаёт валидный ключ невалидным](https://github.com/Tatiana43/hw-1.1/issues/1)
1. [KeyValidator выдаёт валидный ключ невалидным](https://github.com/Tatiana43/hw-1.1/issues/2)
1. [KeyValidator выдаёт невалидный ключ валидным](https://github.com/Tatiana43/hw-1.1/issues/3)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md#%D0%B8%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%86%D0%B8%D1%8F-%D0%BF%D0%BE-%D1%83%D1%81%D1%82%D0%B0%D0%BD%D0%BE%D0%B2%D0%BA%D0%B5-openjdk11)
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D1%80%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-keyvalidator)

В качестве тестовых данных использовались данные [ключи для проверки](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D0%BA%D0%BB%D1%8E%D1%87%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B8):
1. Валидные ключи:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

1. Невалидные ключи:
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Тестирование производилось в следующем окружении:
* ОС Windows 10 x64
* OpenJDK 11.0.9
* [KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class)
* Git
