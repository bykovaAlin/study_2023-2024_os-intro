---
## Front matter
title: "Отчет по лабораторной работе 5"
subtitle: "Операционные системы"
author: "Быкова Алина Александровна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
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
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы
 
Настройка рабочей среды 

# Выполнение лабораторной работы

Установила pass, gopass.

Просмотрела список ключей с помощью команды gpg --list-secret-keys.

Инициализировала хранилище с помощью команды pass init <gpg-id or email>.

Создала структуру git. Выполнила синхронизацию с помощью команд pass git pull
pass git push

Настроила интерфейс с броузером.

Добавила новый пароль; отобразила пароль для указанного имени файла; заменила существующий пароль 

Установила дополнительное программное обеспечение и установила шрифты:
sudo dnf -y install \
     dunst \
     fontawesome-fonts \
     powerline-fonts \
     light \
     fuzzel \
     swaylock \
     kitty \
     waybar swaybg \
     wl-clipboard \
     mpv \
     grim \
     slurp
     
     sudo dnf copr enable peterwu/iosevka
sudo dnf search iosevka
sudo dnf install iosevka-fonts iosevka-aile-fonts iosevka-curly-fonts iosevka-slab-fonts iosevka-etoile-fonts iosevka-term-fonts
 
Установила бинарный файл (sh -c "$(wget -qO- chezmoi.io/get)")

Создала свой репозиторий для конфигурационных файлов на основе шаблона (gh repo create dotfiles --template="yamadharma/dotfiles-template" --private)

Подключила репозиторий к своей системе. 

Использовала chezmoi на нескольких машинах.

Настроила новую машину.

Выполнила ежедневные операции с chezmoi.

# Выводы

Настроила рабочую среду. 

# Список литературы{.unnumbered}

::: {#refs}
:::
