# parser
Небольшой парсер данных с сайта в файл csv

Это скрипт написанный на Python, для парсинга данных с сайтой. Сам скрипт можно доработать как нужно, с учетом страниц которые будет обходить парсер.

Принцип работы, сначала получаем все ссылки с нужной нам страницы, дальше заходим по каждой ссылке и получаем нужную нам информацию. Записываем ее в файл. 

Важно, на первом и вотором этапе, информация записывается в файл. Сначала записываются данные о ссылках, дальше записывается название и описание.

Все что нужно, просто в консоли запустить файл командой pithon parser.py

И в самом файле изменить информацию о ссылке на файл, где будет храниться данные
