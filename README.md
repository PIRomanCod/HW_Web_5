# Файл exchanger.py

Консольна утиліта, яка з публічного АПІ ПриватБанка 
повертає готівковий курс EUR та USD за поточний день.

За допомогою консольних параметрів:

-d 5  - Ви маєте можливість дізнатися курс валют за більшу кількість днів, 
але не більше ніж за останні 10 днів;

-add PLN  - Ви маєте можливість дізнатися курс додаткової валюти

Приклад роботи:
py exchanger.py -d 2 -add TRY


# Чат на веб-сокетах 
з можливістю введення команди: exchange.
Вона показує користувачам поточний курс валют EUR та USD у текстовому форматі.

За допомогою додаткових параметрів команди exchange:
-кількість днів
-додаткова валюта

можливо переглянути курс валют в чаті за останні кілька днів.

Приклад повідомлення у чаті:

exchange 2 CHF

Додане логування до файлу та консолі

