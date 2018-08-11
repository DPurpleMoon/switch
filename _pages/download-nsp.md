---
permalink: /download-nsp.html
title: Закачка игр в формате NSP с помощью CDNSP GUI
author_profile: true
---
{% include toc title="Разделы" %}


### Что понадобится

* Свежая версия программы [CDNSP GUI](files/CDNSP-GUI.zip){:target="_blank"}
* [Python 3.7.0](https://www.python.org/ftp/python/3.7.0/python-3.7.0.exe){:target="_blank"}

#### Часть I - Подготовительные работы

1. Установите Python 3
	* Обязательно отметьте галочкой "Add Python 3.7 to PATH"
1. Перезагрузите ПК
1. Проверьте верно ли установился Python. Для этого в командной строке наберите `py`. Версия должна соответствовать установленной. Если это не так - удалите все установленные версии Python и повторите эту часть с пункта 1
1. Распакуйте `.zip`-архив с программой CDNSP GUI в удобную папку
	* Путь к программе не должен содержать кириллицу
	* Имя учетной записи не должно содержать кириллицу
1. Откройте командную строку от имени администратора 
	* Нажмите `Win+Q` и введите "cmd"
	* Нажмите правой кнопкой мыши на "Командная строка" и выберите "Запуск от имени администратора"
1. С помощью командной строки перейдите в папку с программой CDNSP GUI
	* наберите команду `chdir /d "путь_к_папке_с_программой"`
1. В командной строке наберите `py название_программы.py`
	* На момент написания гайда, самой последней версией программы была 3.5.4 и строка выглядела так: `py CDNSP-GUI-Bob-v3.5.4.py`
1. Скрипт начнёт докачивать необходимые для работы файлы

#### Часть II - Работа с программой CDNSP GUI

1. В открывшемся окне программы введите название игры
	* В правой части окна можно выбрать что именно качать: 	
		* Base game + Update + DLC - выкачать полную версию игры со всеми обновлениями и DLC
		* Base game + Update - выкачать полную версию игры со всеми обновлениями
		* Update + DLC - выкачать только обновления и DLC. Позже их можно установить поверх картриджной версии
		* Base game only- выкачать только игру, без обновлений
		* Update only - выкачать только обновления. Позже их можно установить поверх картриджной версии
		* All DLC - выкачать все имеющиеся DLC
	* Кнопка "Download" начнёт закачку. Скачанная версия игры в формате `.nsp` появится в папке с программой
	* Кнопка "Add to queue" добавит игру в очередь закачки
	* Кнопка "Update Titlekeys" обновит ключи. Если в CDN будет добавлена новая игра - она появится при обновлении ключей. 
	* В меню "Download" -> "Select download location" можно выбрать папку, в которую будут складываться загруженные образы игр
		* В пути к папке не должно быть кириллицы!
	* В меню "Options" выберите "Enable shorten name", чтобы при сохранении играм давались короткие имена, что позволит избежать ошибок в дальнейшем при установке
	* В меню "Options" выберите "Disable Tinfoil Download"
		* Если у вас в опциях "Enable Tinfoil Download", ничего нажимать не нужно	