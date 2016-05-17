# OsmValidator
## Как использовать
1. Поместить папку log в папку куда сохраняются отчеты (по умолчанию рядом с исполнительным файлом).
2. Файлы .osm.pbf расположить рядом с исполнительным файлом.
3. Запустить.

## Описание ключей
regions - список файлов которые надо проверить. Пример: ```region "RU-MOW RU-SA"```

down - файлы будут скачаны с http://gis-lab.info/projects/osm_dump/

upload - отчеты будут загружены на ftp, рядом с исполнительным файлом должен распологаться ```ftp.txt```, где на первой строчке адрес ftp сервера, на второй - логин, на третей - пароль

outdir - путь куда сохранять отчеты

indir - путь откуда брать .osm.pbf файлы
