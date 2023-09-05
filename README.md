# Parc_de_Pavlovsk_WMS
Репозиторий содержит файлы для WMS (по протоколу TMS), образующие слои (картографические материалы) исторических карт [Павловского парка](https://www.openstreetmap.org/relation/1721131).

![Вид в Павловском парке](https://github.com/mkgrgis/Parc_de_Pavlovsk_WMS/assets/41448637/0d8372b6-d046-4e92-b877-b4406e171e8e)

### Пример для картографической библиотеки [Leaflet.js](https://leafletjs.com)
```js
var ParcDePavlovskWMSbaseURL = 'https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS';
L.tileLayer( ParcDePavlovskWMSbaseURL + '/1798/{z}/{x}/{y}.jpg', {
    maxZoom: 20,
    maxNativeZoom: 18,
    attribution: 'Привязка и публикация <a href="http://retromap.ru/1417981_59.685832,30.45423">retromap.ru</a>',
    id: 'Павловск1798'
}),
L.tileLayer(ParcDePavlovskWMSbaseURL + '/1803/{z}/{x}/{y}.jpg', {
    maxZoom: 20,
    maxNativeZoom: 18,
    attribution: 'Привязка и публикация <a href="http://retromap.ru/1418033_59.685832,30.45423">retromap.ru</a>',
    id: 'Павловск1803'
}),
L.tileLayer(ParcDePavlovskWMSbaseURL + '/1842/{z}/{x}/{y}.jpg', {
    maxZoom: 20,
    maxNativeZoom: 17,
    attribution: 'Привязка и публикация <a href="http://retromap.ru/1418421_59.685800,30.453844">retromap.ru</a>',
    id: 'Павловск1842'
}),
L.tileLayer(ParcDePavlovskWMSbaseURL + '/1876/{z}/{x}/{y}.jpg', {
    maxZoom: 20,
    maxNativeZoom: 17,
    attribution: 'Привязка и публикация <a href="http://retromap.ru/14187624_59.685702,30.453672">retromap.ru</a>',
    id: 'Павловск1876'
}),
L.tileLayer(ParcDePavlovskWMSbaseURL + '/1915/{z}/{x}/{y}.jpg', {
    maxZoom: 18,
    maxNativeZoom: 15,
    attribution: 'Привязка и публикация <a href="http://retromap.ru/1418421_59.685800,30.453844">retromap.ru</a>',
    id: 'Павловск1915'
}),
```
### Автоматические ссылки для отрисовки исторических карт в [OpenHistoricalMap ID](https://www.openhistoricalmap.org/edit?editor=id#map=17/59.68542/30.45540)

* Отрисовать по карте 1798 года

https://www.openhistoricalmap.org/edit?editor=id#map=17/59.68542/30.45540&background=custom:https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1798/{z}/{x}/{y}.jpg

* Отрисовать по карте 1803 года

https://www.openhistoricalmap.org/edit?editor=id#map=17/59.68542/30.45540&background=custom:https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1803/{z}/{x}/{y}.jpg

* Отрисовать по карте 1842 года

https://www.openhistoricalmap.org/edit?editor=id#map=17/59.68542/30.45540&background=custom:https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1842/{z}/{x}/{y}.jpg

* Отрисовать по карте 1876 года

https://www.openhistoricalmap.org/edit?editor=id#map=17/59.68542/30.45540&background=custom:https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1876/{z}/{x}/{y}.jpg

* Отрисовать по карте 1915 года

https://www.openhistoricalmap.org/edit?editor=id#map=17/59.68542/30.45540&background=custom:https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1915/{z}/{x}/{y}.jpg

### Реквизиты для ручного добавления слоя подложки в [OpenHistoricalMap ID](https://www.openhistoricalmap.org/edit?editor=id#map=17/59.68542/30.45540)
```
https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1798/{zoom}/{x}/{y}.jpg

https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1803/{zoom}/{x}/{y}.jpg

https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1842/{zoom}/{x}/{y}.jpg

https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1876/{zoom}/{x}/{y}.jpg

https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1915/{zoom}/{x}/{y}.jpg
```

### Автоматические ссылки для датировки объектов в OpenStreetMap редакторе ID

* Датировать по карте 1798 года

https://www.openstreetmap.org/edit?editor=id#map=17/59.68542/30.45540&background=custom:https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1798/{z}/{x}/{y}.jpg

* Датировать по карте 1803 года

https://www.openstreetmap.org/edit?editor=id#map=17/59.68542/30.45540&background=custom:https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1803/{z}/{x}/{y}.jpg

* Датировать по карте 1842 года

https://www.openstreetmap.org/edit?editor=id#map=17/59.68542/30.45540&background=custom:https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1842/{z}/{x}/{y}.jpg

* Датировать по карте 1876 года

https://www.openstreetmap.org/edit?editor=id#map=17/59.68542/30.45540&background=custom:https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1876/{z}/{x}/{y}.jpg

* Датировать по карте 1915 года

https://www.openstreetmap.org/edit?editor=id#map=17/59.68542/30.45540&background=custom:https://mkgrgis.github.io/Parc_de_Pavlovsk_WMS/1915/{z}/{x}/{y}.jpg
