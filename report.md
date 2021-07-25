# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

10.07.2021 - 10.07.2021 было проведено Unit testing приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие [дефекты](https://github.com/alexkv2602/Credit-Card-Number-Validator/issues) :
* Программа проверки карт не принимает карты имеющие не 16-ти цифровые значения


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Набор валидных карт](https://github.com/alexkv2602/Credit-Card-Number-Validator/blob/master/cards%20number.html) 




В качестве тестовых данных использовались данные валидных карт с сайта [с сайта](https://www.freeformatter.com/credit-card-number-generator-validator.html):
VISA:
* 4539229506774006 result is ok

* 4916319296080749 result is ok

* 4819639227209911509 result is fail

Visa Electron:
* 4175008824558468 result is ok

* 4026031433838015 result is ok

* 4844530270967001 result is ok

MasterCard:
* 5406513208925769 result is ok

* 5203712296248747 result is ok

* 2720999505739167 result is ok

Maestro:
* 6763630960787800 result is ok

* 5038427289248072 result is ok

* 0604705253794261 result is ok

JCB:
* 3535052713223641 result is ok

* 3529034545238623 result is ok

* 3534689744089799486 result is fail

American Express (AMEX):
* 377816302160183 result is ok

* 373926898919332 result is ok

* 377061947709587 result is ok

Тестирование производилось в следующем окружении:
* Windows 10, 64-ядерная операционная система,
* Openjdk version "11.0.11" 2021-04-20
* IntelliJ IDEA 2021.1.1 (Commynity Edition)
