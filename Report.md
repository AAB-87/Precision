Отчёт о тестировании Precision

Краткое описание:

14.07.21 20:55 - 14.07.21 21:00 было проведено ручное тестирование приложения Precision.
На тестирование затрачено: 0,083 ч

В результате тестирования выявлены следующие дефекты:

* [Отражается неверная сумма при сложении регулярного и дополнительного бонуса для новых клиентов](https://github.com/AAB-87/Precision/issues/2)


В качестве тестовых данных использовались данные указанные в задании 2 домашнего задания:

* double regularBonus = 0.3;
* double specialBonus = 0.6.
  
Тестирование производилось в следующем окружении:

* Windows 7 (Максимальная), Intel(R) Core(TM) i3-2348M CPU @ 2.30 GHz, 64bit
* Java 11.0.11 2021-04-20