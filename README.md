Для простоты я ввел некоторые ограничения и допущения:
1) Все счета привязаны к одной валюте (российский рубль);
2) Нет аутентификации с авторизацией;
3) Перевод, пополнение и снятие денег со счета осуществляется без комиссий;
4) Счета все действительны;
5) Нельзя совершать операцию перевода, если номера счетов одинаковые;
6) Считаем, что сумма обрезается до 2х знаков после запятой.


Запустив  приложение c профилем test, можно протестировать API с помощью spring fox интерфейса:
http://localhost:8099/swagger-ui.html

В приложении есть 2 счета с номерами 11112222333344445555 и 11112222333344445556