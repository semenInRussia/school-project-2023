# Шаблон для создания latex документов по ГОСТ

Данный шаблон является форком [этого шаблона](http://sevik.ru/latex/)

На данный момент поддерживаются только UNIX-системы

Общая информация:

* Сбор проекта происходит скриптом `build.sh`
* Все tex-файлы находятся в папке tex
* Изображения, файлы с кодом и другие сторонние файлы помещаются в папку inc
* Eps-файлы автоматически конвертируются в pdf.
* Фильтрация ошибок и предупреждений

Что пока не поддерживается:

* Windows
* Поддиректории

Как происходит сборка:

1. В папку `tex/` копируются файлы из `gost/` и `inc/`
2. Сборка pdflatex + bibtex
3. Очистка `tex/`
