# ALLINMenu 1.0.0
Paper 26.2 / Java 25

## Игрок
/menu

## Админ — Мастера обмена
Встаньте ТОЧНО в точку, куда должен телепортироваться игрок:
/allinmenu master set food Мастер еды
/allinmenu master set ores Мастер руды
/allinmenu master rename food Новый мастер еды
/allinmenu master delete food
/allinmenu master list
/allinmenu reload

Телепортация по умолчанию 30 секунд. При попытке изменить X/Y/Z игрок остаётся на месте, а телепортация отменяется.
Поворот камеры разрешён.

## Настройка информации
plugins/ALLINMenu/menu.yml — пункты главного GUI и информационные страницы.
plugins/ALLINMenu/masters.yml — точки мастеров (создаются командами).
plugins/ALLINMenu/config.yml — таймер и сообщения.
