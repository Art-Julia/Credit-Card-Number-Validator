# Отчёт о тестировании "Валидация номера банковской карты"

## Проверка функционала внесения номера банковской карты следующих платежных систем: VISA, Mastercard, Discover, Diners Club - Carte Blanche, Visa Electron, JCB, Diners Club - International, InstaPayment, American Express (AMEX), Diners Club - North America, Maestro

09.05.2021 было проведено функциональное тестирование на основе классов эквивалентности приложения приема платежей банковских карт.

На тестирование затрачено: 1  час

В результате тестирования выявлены следующие дефекты:
* [14ти значный номер карты не валидируется](https://github.com/Art-Julia/Credit-Card-Number-Validator/issues/3)
* [15ти значный номер карты не валидируется](https://github.com/Art-Julia/Credit-Card-Number-Validator/issues/1)
* [19ти значный номер карты не валидируется](https://github.com/Art-Julia/Credit-Card-Number-Validator/issues/2)

## Описание процесса тестирования

В процессе тестирования использовались следующий артефакт:
* [чек-лист](https://docs.google.com/spreadsheets/d/1FuIBf9K5iRMabpsXz4xnWNQ-kGuKebQ8ZoqmynvkbKw/edit?usp=sharing) 


В качестве тестовых данных использовались данные freeformatter.com/credit-card-number-generator-validator.html :
* 16ти значный номер карты 4913794631933708,
* 14ти значный номер карты 30425329394459, 
* 15ти значный номер карты 344851722392611,
* 19ти значный номер карты 3540966720984021425,


Тестирование производилось в следующем окружении:
* macOS Big SUr v. 11.2.3
* Java 11.0.2
