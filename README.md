# Torrent Autoremove Tool


v. 1.1.0

Скрипт для удаления старых торрентов по заданным условиям. 
Работает с μTorrent и Bittorrent клиентами. 


## Настройка скрипта
1. Скачать и устанавить [Python](https://www.python.org/downloads/) последней версии. При установке обязательно добавить запись в **PATH**.
2. Скачать данный репозиторий через **git** или архив (_Code_ -> _Download ZIP_).
3. В настройках торрент-клиента открыть _Дополнительно_ -> _Веб-интерфейс_, поставить галочку _Использовать веб-интерфейс_. 
4. Указать произвольный логин, пароль и порт (лучше использовать нестандартный).
5. Указать логин, пароль, порт, максимальное число торрентов, свободное место на диске (GB) в файле **config.json** через текстовый редактор.
6. Запустить файл _INSTALL.bat_ для установки необходимых модулей (только один раз).
7. Запустить файл _START.bat_.

Логирование процесса идет в файл **app\log.txt**.
