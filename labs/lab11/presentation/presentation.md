---
## Front matter
lang: ru-RU
title: Отчет по лабораторной работе 11
subtitle: Операционные системы 
author:
  - Быкова А.А.
institute:
  - Российский университет дружбы народов, Москва, Россия
 
## i18n babel
babel-lang: russian
babel-otherlangs: english

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

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Быкова Алина Александровна 
  * студент
  * Российский университет дружбы народов

:::
::: {.column width="30%"}


:::
::::::::::::::

## Цели и задачи

Познакомиться с операционной системой LINUX. Получить практические навыки работы с редактором Emacs.

## Выполнение лабораторной работы

Открыла emacs. Создала файл lab11.sh.

Набрала текст: 1 #!/bin/bash
2 HELL=Hello
3 function hello {
4 LOCAL HELLO=World
5 echo $HELLO
6 }
7 echo $HELLO
8 hello

Сохранила файл.

Проделала с текстом стандартные процедуры редактирования:
5.1. Вырезать одной командой целую строку (С-k).
5.2. Вставить эту строку в конец файла (C-y).
5.3. Выделить область текста (C-space).
5.4. Скопировать область в буфер обмена (M-w).
5.5. Вставить область в конец файла.
5.6. Вновь выделить эту область и на этот раз вырезать её (C-w).
5.7. Отмените последнее действие (C-/)

Научилась использовать команды по перемещению курсора.

Управляла буферами.

Управляла окнами.

Использовала режим поиска.


## Выводы

Познакомилась с операционной системой LINUX. Получила практические навыки работы с редактором Emacs.
