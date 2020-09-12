# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

<20:42 08.09.2020> - <20:59 08.09.2020> было проведено функциональное тестирования приложения <Credit Card Number Validator>. 

Тестировались валидные карты:
* VISA
* Discover
* Diners Club - Carte Blanche
* Visa Electron

На тестирование затрачено: <15 минут>

В результате тестирования выявлены следующие дефекты:
https://github.com/ZSemen47/Credit-Card-Number-Validator/issues/1#issue-698218645

## Описание процесса тестирования

В качестве тестовых данных использовались данные с сайта freeformatter.com:
* String number = "4916326481211609" Result is OK
* String number = "6011651179008739" Result is OK
* String number = "30380484788328" Result is OK
* String number = "4844983770285970" Result is OK

* Тестирование производилось в следующем окружении:

<Windows 10 pro>
<версия Java 11.0.7>