---
## Front matter
lang: ru-RU
title: Отчет по лабораторной работе №1
author: Deryabina Maria
institute: RUDN University, Moscow, Russian Federation
date: 13 February, 2021

## Formatting
mainfont: Times New Roman
romanfont: Times New Roman
sansfont: Times New Roman
monofont: Times New Roman
toc: false
slide_level: 2
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Markdown

## Базовые сведения о Markdown

- Чтобы создать заголовок, используется знак (#)
- Чтобы задать для текста полужирное начертание, его заключают в **двойные звездочки**
- Чтобы задать для текста курсивное начертание, его заключают в *одинарные звездочки*
- Чтобы задать для текста полужирное и курсивное начертание, его заключают в ***тройные звездочки***
- Неупорядоченный (маркированный) список можно отформатировать с помощью звездочек или тире

## Базовые сведения о Markdown

1. Упорядоченный список можно отформатировать с помощью соответствующих цифр

2. Синтаксис Markdown для встроенной ссылки состоит из части \[link text], представляющей текст гиперссылки, и части(file-name.md) – URL-адреса или имени файла, на который дается ссылка


## Обработка файлов в формате Markdown

- Для обработки файлов в формате Markdown будем используется Pandoc
- Преобразовать файл README.md можно следующим образом:
	- pandoc report.md -F pandoc-crossref -o report.docx    
	- pandoc report.md -F pandoc-crossref -o report.pdf

# Git и Github

## Для чего используется git

Git — распределённая система контроля версий, которая даёт возможность разработчикам отслеживать изменения в файлах и работать совместно с другими разработчиками

## Что такое Github

GitHub — сервис онлайн-хостинга репозиториев, обладающий всеми функциями распределённого контроля версий и функциональностью управления исходным кодом

## Создание репозитория

- Чтобы создать git репозиторий из этого каталога, необходимо выполнить команду git init.

## Добавление файла в репозиторий

- git add hello.html
- git commit -m "Initial Commit"

## Подключение репозитория к Github

git remote add origin <Путь директории>

## Отправка файлов на Github

git push -u origin <Ветка>

## Проверка состояние репозитория

git status

