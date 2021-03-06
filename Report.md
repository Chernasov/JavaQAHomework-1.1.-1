# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

<07.08.2021> - <07.08.2021> было проведено позитивное функциональное тестирование 
приложения Credit Card Number Validator.

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
* [Банковские карты American Express не проходят валидацию](https://github.com/Chernasov/JavaQAHomework-1.1.-1/issues/1#issue-963212547)
* [Банковские карты JSB с количеством цифр в номере больше 16 не проходят валидацию](https://github.com/Chernasov/JavaQAHomework-1.1.-1/issues/2#issue-963213660)
* [Банковские карты China Union Pay с количеством цифр в номере больше 16 не проходят валидацию](https://github.com/Chernasov/JavaQAHomework-1.1.-1/issues/3#issue-963214230)
* [Банковские карты Maestro с количеством цифр в номере не равным 16 не проходят валидацию](https://github.com/Chernasov/JavaQAHomework-1.1.-1/issues/4#issue-963214508)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [чек-лист](https://github.com/Chernasov/JavaQAHomework-1.1.-1/blob/6ed962682d1c61cae31d86a592391fba89e834ec/src/test/Chek-list.md)

В качестве тестовых данных использовались данные <https://cardguru.io/>:
* данные генерировались на указанном сайте, перечень платежных систем перечислен в чек-листе, ожидалось, что все сгенерированные данные пройдут проверку с результатом "ОК".

Тестирование производилось в следующем окружении:
* 20H2 x64 Windows 10 Домашняя для одного языка
* Java version "11.0.11" 2021-04-20
