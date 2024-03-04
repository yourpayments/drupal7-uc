# «Твои платежи», модуль для CMS Drupal 7 Ubercart

![](https://repository-images.githubusercontent.com/638835276/ff494b04-d65b-4843-8759-e85c689a7e80)

[НКО «Твои Платежи»](https://YPMN.ru/ "Платёжная система для сайтов, платформ и приложений") - платёжная система для сайтов, платформ, игр и приложений.

!! Внимание !!
Для мерчантов из России обязательно нужно указать ссылку LU и валюту мерчанта.
 

( Проверено на версиях 1.5.х )

IPN : http://{домен сайта}/uc_payu/ipn_url
или
IPN : http://{домен сайта}/?q=uc_payu/ipn_url



#Установка
-------------
1. Скопировать папку uc_payu в /{корень сайта}/modules/ubercart/
2. Зайти в админку сайта
2.1 Выбрать меню "Модули"
2.2 Выбрать метод оплаты PayU и установить
![Установка][0]
3. Перейти в раздел "Магазин"
![Магазин][1]
3.1 Выбрать настройку PayU
3.2 Ввести данные для конфигурации модуля
![Конфигурация][2]
4. Вернутся в раздел "Магазин"
4.1 Выбрать настройку "Платежные методы"
![Платежи][3]
4.2 Включить метод PayU



[0]: https://raw.github.com/yourpayments/drupal7-uc/master/screenshot0.png
[1]: https://raw.github.com/yourpayments/drupal7-uc/master/screenshot1.png
[2]: https://raw.github.com/yourpayments/drupal7-uc/master/screenshot2.png
[3]: https://raw.github.com/yourpayments/drupal7-uc/master/screenshot3.png