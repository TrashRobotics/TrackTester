<h1 align="center">
  <a href="ссылка на видео"><img src="https://github.com/TrashRobotics/TrackTester/blob/main/img/ttest.jpg" alt="Тестер гусениц" width="800"></a>
  <br>
  Тестер гусениц
  <br>
</h1>

<p align="center">
  <a href="https://github.com/TrashRobotics/TrackTester/blob/main/README.md">Русский</a> •
  <a href="https://github.com/TrashRobotics/TrackTester/blob/main/README-en.md">English(Английский)</a> 
</p>

# Описание проекта
Программы тележки для тестирования гусениц

# Основные детали тележки
* arduino Nano v3;
* bluetooth модуль HC-06;
* драйвер двигателей MX1508;
* желтые ардуино TT-мотор-редукторы;
* 2x 18650 аккумуляторы и батарейный отсек для них
* тумблер;
* доска или кусок фанеры 190x80 мм;
* [колеса, крепления и прочеее](ссылка на детали)

### Крепеж
* Подшипник 623 2RS (180023) 3dx10Dx4H x2;
* Саморез DIN7982 3.5x16 x10;
* Саморез DIN7982 2.2x9.5 x2; 
* Винт DIN7985 M3x35 x6;
* Винт DIN7985 M3x30 x8;
* Винт DIN7985 M3x12 x12;
* Гайка DIN934 M3x0.5 x30;

# Проги
Прошивка для arduino Nano: **track_test/track_test.ino**            
**tracktester.py** - скрипт на python для управления тележкой с ПК.            
Для запуска скрипта необходимо установить пакет **punput**.              
Управление тележкой осуществляется стрелочками.

