# Parc_de_Pavlovsk_WMS
Картографические материалы по Павловскому парку

### WMS слои исторических карт Павловского парка
Пример для картографической библиотеки [Leaflet.js](https://leafletjs.com)
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
