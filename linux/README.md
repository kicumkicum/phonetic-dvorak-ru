# Установка

Источник: https://www.linux.org.ru/forum/desktop/9341826

1. по подсказке товарища, ищем, где находиться файл раскладки:
`dpkg -L xkb-data | grep ru` или `find /usr/share -name ru | grep xkb`
у меня файл раскладки оказался тут: `/usr/share/X11/xkb/symbols/ru` 

2. Скачиваем отсюда файл раскладки дворака https://bugs.launchpad.net/ubuntu/+source/xkeyboard-config/+bug/319376/+attachment/442526/+files/lng.tar
(кому интересно, сам топик тут https://bugs.launchpad.net/ubuntu/ source/xkeyboard-config/ bug/319376 )
распакуем, копируем файл `ru` вместо существующего файла раскладки. 

3. `xkeybmap "us,ru(phonetic_dvorak)"`

4. PROFIT :)
