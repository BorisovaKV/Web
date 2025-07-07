# Тестирование веб-приложений

Я протестировала веб приложение https://qa.demoshopping.ru/ и подготовила различные виды тестовой документации. Помимо этого в рамках работы с Charles и Proxyman я перехватила и изменила трафик для этого же интернет-магазина

[Тест план](https://docs.google.com/spreadsheets/d/1fl66kWqvH1_Oa10T3v6SNVLysC0QrHn7XJ2aAFCcPm4/edit?usp=sharing), описывающий, что нужно протестировать и как тестировать, был составлен на основе [описания проекта](https://docs.google.com/document/d/1pI4AkQ5eHTGw5YDL_uTpP_L-M1aQz_ehFrZgntw9lG4/edit?tab=t.0) и требований

[Чек-лист](https://docs.google.com/spreadsheets/d/1WD5pXMVAE_-vEgIqOL2iO0Y3KAqWbmxm5Vp-oiD2dFc/edit?gid=0#gid=0)

[Тест-кейсы](https://drive.google.com/file/d/10z00u2wllhE1uhEGTLUmaf8wpPvcYKch/view?usp=drive_link) для регистрации и авторизации, а также каталога
[Тест-кейсы](https://drive.google.com/file/d/10z00u2wllhE1uhEGTLUmaf8wpPvcYKch/view?usp=drive_link) для управления корзиной и управления заказами

[Тестовый прогон](https://drive.google.com/file/d/1YI8bry475aBn_OA5Q4B1Fm4HdSnSEXiF/view?usp=sharing) для регистрации и авторизации, а также каталога

[Отчёты о дефектах](https://docs.google.com/spreadsheets/d/1FNBxg2tT4gavqixDngZTndnmbB_5b3-Z/edit?usp=sharing&ouid=116268271765014270767&rtpof=true&sd=true) для интернет-магазина, оформленные через YouTrack 

[Перехват и изменение трафика](https://drive.google.com/file/d/1hBvm6kNnV3xQGeAeEp5H8_7jfh_41yOa/view?usp=sharing) выполнены на основе заданных условий: изменение количества товаров в корзине (отправляется "2" товара, возвращается "500"), проверка реакции сервера при обращении к [Prod](https://demoshopping.ru/) (ожидаемый статус-код 403), а также перенаправление запроса с [Prod](https://demoshopping.ru/) на [QA](https://qa.demoshopping.ru/)

