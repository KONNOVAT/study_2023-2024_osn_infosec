---
## Front matter
lang: ru-RU
title: Презентация по Этапу №2 ИП
subtitle: Основы информационной безопасности
author:
  - Коннова Татьяна Алексеевна
date: 16 марта 2024

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Коннова Татьяна Алексеевна
  * НПИбд-01-22
  
:::
::: {.column width="30%"}

:::
::::::::::::::

## Цель работы

- Установить DVWA в гостевую систему к Kali Linux.


# Выполнение работы

## Клонирование репо

![Переход, клонирование](image/1.png){#fig:001 width=50%}


## Изменение config.inc.php

![config.inc.php](image/2.png){#fig:002 width=50%}


## mariadb

![mariadb](image/3.png){#fig:003 width=70%}


## БД

![БД](image/4.png){#fig:004 width=70%}

## Настройка сервера

![Apache](image/5.png){#fig:005 width=60%}

## Изменение параметров

![php.ini](image/6.png){#fig:006 width=60%}

## Заполнение параметров входа в браузере

![Заполнение параметров входа в браузере](image/7.png){#fig:007 width=70%}

## Заполнение параметров входа в браузере

![Вход](image/8.png){#fig:008 width=70%}

## Заполнение параметров входа в браузере

![Hello page](image/9.png){#fig:009 width=70%}

## Выводы

- В ходе выполнения данной лабораторной работы проведена установка DVWA в Kali Linux.

