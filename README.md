Тестовое задание
==================

В файле в формате JSON находятся данные о треке в виде массива координат и скоростей.
Приложение отображает карту и поверх этой карты рисует трек по полученным данным.
Участки трека с разными скоростями рисуются разными цветами:
если скорость ниже или равна 60 км/ч — зелёный;
если скорость ниже или равна 120 км/ч — жёлтый;
дальше — красный.

Формат данных в файле следующий:
- Все временные метки в unixtime.
- start — дата начала трека;
- end — дата окончания трека;
- length — длина трека;
- count — количество точек трека;
- max_speed — максимальная скорость;
- points — массив точек трека:
- lat — широта;
- lng — долгота;
- date — дата снятия точки;
- speed — скорость в данной точке.

Приложение из одного ViewController'а с NavigationBar. ViewController отображает карты Google Maps.
По полученным данным рисуется трек поверх карты Google Maps.
Трек перерисовывается, когда пользователь перемещает или масштабирует карту(изменяется толщина).
В NavigationBar находится меню из одной кнопки, по нажатию на которую открывается диалог со следующей информацией: длина трека (в километрах), максимальная скорость на треке, дата начала трека и дата конца трека в формате "dd MM yyyy: HH:mm-HH:mm".
Приложение работает под iOS.
Приложение работает в портретном и ландшафтном режимах вне зависимости от устройства, на котором оно выполняется (телефон или планшет).


Сторонние библиотеки: Google Maps

### Тестовые данные были изменены для наглядности решения

![Загрузка](/screenshots/1.png "")
![Трек](/screenshots/2.png "")
![Информация о треке](/screenshots/3.png "")
![Изменение масштаба и толщины трека](/screenshots/4.png "")