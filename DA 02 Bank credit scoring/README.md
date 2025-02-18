# Анализ платёжеспособности заёмщиков

[ipynb](https://github.com/volovik-denis/yandex-practicum/blob/main/DA%2002%20Bank%20credit%20scoring/Исследование%20надёжности%20заёмщиков.ipynb)

## Описание проекта

Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.

Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

## Навыки и инструменты

- **python**
- **pandas**
- **numpy**
- matplotlib.**pyplot**
- **seaborn**
- nltk.stem.**SnowballStemmer**
- pymystem3.**Mystem**

## Вывод

При решении, одобрять ли кредит клиенту, в первую очередь нужно учитывать его семейное положение, которое непосредственно влияет на погашение кредита в срок. Наилучшими клиентами, которые с большей вероятностью будут погашать кредит в срок, будут люди без детей, состоявшие в браки ранее, с уровнем дохода в 200001–1000000, а также их кредит должен быть для операций с недвижимостью. Самыми худшими же клиентами будут не женатые/замужние с детьми, их уровень дохода будет составлять от 50001 до 200000, а также их цель кредита это соверешние операций с машинами.

## Статус проект - завершён
