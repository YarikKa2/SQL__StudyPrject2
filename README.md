# Анализ базы данных с платформы HeadHunter с использованием SQL
Анализ базы данных выгруженных с сайта поиска вакансий hh.ru.  <br>
В проекты был произведен базовый анализ с использованием PostgreSQL.

## Содержание
- [Технологии](#технологии)
- [Использование](#Использование)
- [Команда проекта](#команда-проекта)
- [Дополнительно](#Дополнительно)

## Технологии
- [Visual Studio Code](https://code.visualstudio.com/)
- [Python 3.9.10](https://www.python.org/downloads/release/python-3910/)
- [psycopg2](https://pypi.org/project/psycopg2/)

## Использование
Для работы данной программы потребуется импортировать несколько библиотек <br>
pandas ``` import pandas as pd ``` <br>
plotly.express ``` import plotly.express as px ``` <br>
psycopg2 ``` import psycopg2 ``` <br>
requests ``` import requests ``` <br>
BeautifulSoup ``` from bs4 import BeautifulSoup ``` <br>
<br>
Если у вас отсутвует какой либо из вышеперечисленных пакетов, установите его. <br>
В терминале введите ``` pip install 'название_пакета_без_кавычек' ```<br>

Для работы plotly требуется <ins>**nbformat**</ins> (версия 4.2.0 или выше), <ins>**lxml**</ins>, <br>а также kaleido для сохранения изображений в png <br>
Для установки nbformat введите в терминале ``` pip install nbformat ``` <br>
Для установки kaleido введите в терминале ``` pip install -U kaleido ``` <br>
<br>
Если, при использовании Windows 10, возникли проблемы с сохранением файлов в png, установите версию kaleido 0.1.0<br>
Файл с необходимой версией находится в корневой папке проекта. Для установки выполните в терминале ```pip install kaleido-0.1.0.post1-py2.py3-none-win_amd64.whl```

<br>
Обязательно перезагрузите kernel после установки (либо перезагрузите Visual Studio Code)

## Команда проекта

[Капущак Ярослав](https://github.com/YarikKa2)

## Дополнительно
Может помочь в случае возникновения проблем с nbformat: <br> [ValueError: Mime type rendering requires nbformat>=4.2.0 but it is not installed](https://stackoverflow.com/questions/66557543/valueerror-mime-type-rendering-requires-nbformat-4-2-0-but-it-is-not-installed)
Может помочь в случае возникновения проблем с kaleido: <br> [Static image export hangs using kaleido](https://community.plotly.com/t/static-image-export-hangs-using-kaleido/61519)
