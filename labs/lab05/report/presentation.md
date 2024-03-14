---
## Front matter
lang: ru-RU
title: Структура научной презентации
subtitle: Простейший шаблон
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


## Цель

Настройка рабочей среды

## Выполнение лабораторной работы 

Установила pass, gopass.
Просмотрела список ключей с помощью команды gpg –list-secret-keys.
Инициализировала хранилище с помощью команды pass init .
Создала структуру git. Выполнила синхронизацию с помощью команд pass git pull
pass git push
Настроила интерфейс с броузером.
Добавила новый пароль; отобразила пароль для указанного имени файла; заменила
существующий пароль
Установила дополнительное программное обеспечение и установила шрифты: sudo
dnf -y install
dunst
fontawesome-fonts
powerline-fonts
light
fuzzel
swaylock
kitty
waybar swaybg
wl-clipboard
mpv
grim
slurp
sudo dnf copr enable peterwu/iosevka
sudo dnf search iosevka sudo dnf install iosevka-fonts iosevka-aile-fonts iosevka-curly-
fonts iosevka-slab-fonts iosevka-etoile-fonts iosevka-term-fonts
Установила бинарный файл (sh -c “$(wget -qO- chezmoi.io/get)”)
Создала свой репозиторий для конфигурационных файлов на основе шаблона (gh
repo create dotfiles –template=“yamadharma/dotfiles-template” –private)
Подключила репозиторий к своей системе.
Использовала chezmoi на нескольких машинах.
Настроила новую машину.
Выполнила ежедневные операции с chezmoi.

##  Выводы 

Настроила рабочую среду.
