# Отчёт о тестировании "Credit Card Number Validator"

## Краткое описание

11.08.2021 - 11.08.2021 было проведено функциональное тестирование приложения "Credit Card Number Validator".

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
[Не принимается платёжная система American Express при вводе валидного номера карты](https://github.com/Axolotlick/Credit-Card-Number-Validator/issues/1#issue-967042159)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Тест-план](https://docs.google.com/spreadsheets/d/1ahNQma7AJzHSRqBkH-14KcczDbbix_9VFcT5Li0Wtcw/edit?usp=sharing)
* [Баг-репорт](https://github.com/Axolotlick/Credit-Card-Number-Validator/issues/1#issue-967042159)

В качестве тестовых данных использовались данные [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html) :
* 4916892124811261 
* 2221002634211358
* 6011012099327859 
* 3529121318882404 
* 5425783057409994
* 6373810317477501

Тестирование производилось в следующем окружении:
* версия и разрядность ОС: Windows 10 (20H2), 64-разрядная;
* версия Java: 11.0.12+7.
