**Задача №3**

В папке лежит некоторое количество файлов. Считайте, что их количество и имена вам заранее известны, пример для выполнения домашней работы можно взять тут

Необходимо объединить их в один по следующим правилам:

1. Содержимое исходных файлов в результирующем файле должно быть отсортировано по количеству строк в них (то есть первым нужно записать файл с наименьшим количеством строк, а последним - с наибольшим)
2. Содержимое файла должно предваряться служебной информацией на 2-х строках: имя файла и количество строк в нем

Пример Даны файлы: 1.txt
```
Строка номер 1 файла номер 1
Строка номер 2 файла номер 1
```
2.txt
```
Строка номер 1 файла номер 2
```
Итоговый файл:
```
2.txt
1
Строка номер 1 файла номер 2
1.txt
2
Строка номер 1 файла номер 1
Строка номер 2 файла номер 1
```