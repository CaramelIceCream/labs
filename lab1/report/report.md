---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе"
subtitle: "Лабораторная №1"
author: "Дерябина Мария Сергеевна"

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: Times New Roman
romanfont: Times New Roman
sansfont: Times New Roman
monofont: Times New Roman
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Вспомнить использование Git и Markdown, научиться конвертировать файлы из Markdown в Docx и Pdf.


# Задание

- Написать отчет по лабораторной работе и презентацию в Markdown.
- Конвертировать файлы из md в docx и pdf с использованием Pandoc.
- Создать репозиторий на GitHub и загрузить в него файлы лабораторной работы.


# Выполнение лабораторной работы

1. Склонировала шаблоны отчета лабораторной работы и презентации(рис. -@fig:001)

![Клонирование](image/clone.png){#fig:001 width=70%}



2. Установила программу pandoc для конвертации файлов из md в pdf и docx(рис. -@fig:002).

![Установка Pandoc](image/pandoc.png){#fig:002 width=70%}



3. Создала репозиторий для лабораторных работ на GitHub(рис. -@fig:003).

![Репозиторий](image/github.png){#fig:003 width=70%}



4. Сделала отчет и презентацию по лабораторной работе в формате Markdown.



5. Сконвертировала файлы из md в docx и pdf.

![Конвертация](image/convert.png){#fig:004 width=70%}


6. Загрузила файлы лабораторной работы в репозиторий.



# Вывод

Я вспомнила использование git и markdown, научилась конвертировать файлы в другие форматы с помощью программы pandoc, научилась работать с Github.
