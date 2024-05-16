# МИПиС
## mod-lab05-gen

![GitHub pull requests](https://img.shields.io/github/issues-pr/UNN-IASR/mod-lab05-gen)
![GitHub closed pull requests](https://img.shields.io/github/issues-pr-closed/UNN-IASR/mod-lab05-gen)

Срок выполнения задания:

**до 16.04** ![Relative date](https://img.shields.io/date/1681678800)

## Lab 05. Генератор текста на основе n-грамм

В данной работе нужно разработать три класса, каждый из которых представляет собой генератор текста, работающий по определенному алгоритму. Входные данные для алгоритмов скачиваются по адресам, указанным в задании. 

Метод **Main** должен последовательно вызывать методы генерации из 3-х классов и создавать 3 выходных файла с текстом, объемом не менее 1000 единиц. Эти файлы прикладываются к заданию.


### Задача №1

> Разработать генератор текста на основе пар букв (биграмм). Используются вероятностные свойства сочетаний пар символов.

Данные по биграммам можно взять отсюда: http://statistica.ru/local-portals/data-mining/analiz-tekstov/

Они представлены в виде таблицы и сведены к весам, что облегчает обработку для случайного генерирования.

### Задача №2

> Разработать генератор текста на основе частотных свойств слов 

Данные о частотах (топ-100) можно взять отсюда:

https://ruscorpora.ru/new/1grams.top.html

### Задача №3

> Разработать генератор текста на основе частотных свойств пар слов 

Данные о частотах (топ-100) можно взять отсюда:

https://ruscorpora.ru/new/2grams.top.html

### Задача №4 (Тестирование)

- Добавить в решение .NET проект с тестами (за основу взять пример из **mod-lab02-fa-csharp**)
- Разработать не менее 6 тестов (чем больше, тем лучше)


