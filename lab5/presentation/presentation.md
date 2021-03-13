---
## Front matter
lang: ru-RU
title: Отчет по лабораторной работе №5
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

## Цель работы

Цель данной лабораторной работы - ознакомиться с моделью типа "хищник-жертва" - моделью Лотки-Вольтерры.

## Задачи лабораторной работы  

Задачей данной лабораторной работы было построить графики данной модели:

1. График изменения численности хищников и жертв.
2. График зависимости численности хищников от численности жертв.
3. График стационарного состояния системы.

## Модель

$\begin{cases} \frac{dx}{dt}=-ax(t)+bx(t)y(t)\\\frac{dy}{dt}=cy(t)-dx(t)y(t) \end{cases}$

Коэффициент $c$ описывает скорость естественного прироста числа жертв в отсутствие хищников

$a$ - естественное вымирание хищников, лишенных пищи в виде жертв

Вероятностьвзаимодействия жертвы и хищника считается пропорциональной как количеству
жертв, так и числу самих хищников ($xy$). Каждый акт взаимодействия уменьшает
популяцию жертв, но способствует увеличению популяции хищников (члены $bxy$
и $-dxy$ в правой части уравнения). 

# Результаты

## График изменения численности хищников и жертв.

![](image/1.png){#fig:001 width=70%}

## График зависимости численности хищников от численности жертв.

![](image/2.png){#fig:002 width=70%}

## График стационарного состояния системы.

![](image/3.png){#fig:003 width=70%}

## Выводы

Я изучила модель "хищник-жертва", проанализировала изменение двух популяций в зависимости от времени и друг друга.

