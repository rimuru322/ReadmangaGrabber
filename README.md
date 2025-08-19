# Manga Grabber (v2) 

Утилита для скачивания манги с сайтов ReadManga, MintManga и SelfManga.
На 19.08.25 работают zazaza, selfmanga, mintmanga (с авторизацией).

## Возможности

* Скачивание целой манги / указанного списка глав из манги
* Создание PDF файлов для скачанных глав
* Создание CBZ файлов для скачанных глав

**Возможности скачивания платной манги нет и не будет!**

## Использование

* Скачать последнюю версию для вашей ОС из [раздела релизов](https://github.com/rimuru322/ReadmangaGrabber/releases/latest)
* Распаковать в удобное место
* Запустить исполняемый файл (grabber_win_x64.exe, grabber_linux_x64 или grabber_osx_x64)

## Сохранение cookies для ReadManga/MintManga

1. Войдите со своими логином/паролем на нужный сайт
2. Для сохранения cookies в файл используйте расширение браузера (например, для Chrome и аналогов: [Get cookies.txt LOCALLY](https://chrome.google.com/webstore/detail/get-cookiestxt-locally/cclelndahbckbenkjhflpdbgdldlbecc), для FireFox: [cookies.txt](https://addons.mozilla.org/ru/firefox/addon/cookies-txt/))
3. Сохраненный файл переименуйте соответственно домену нужного сайта с расширением .txt, например, readmanga.live.txt или mangalib.me.txt, и положите в папку с программой

В случае если у вас есть сохраненный файл с cookies, но манга не скачивается вероятно истек срок действия cookies, сохраните их еще раз.

![Интерфейс](https://raw.githubusercontent.com/lirix360/ReadmangaGrabber/gh-pages/screenshot-v2.png)

## Компиляция из исходного кода

* Установите [последнюю версию](https://go.dev/dl) языка Go
* Скачайте исходный код в удобное место с помощью git или в виде zip-файла
* Запустите файл сборки соответствующий вашей ОС (build_win.bat, build_linux.sh или build_osx.sh)
* Скомпилированная версия утилиты появится в папке builds/ваша_ОС
