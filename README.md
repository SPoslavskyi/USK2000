# USK2000

Відповідно до наказу Міністерства аграрної політики та продовольства Українивід 02.12.2016 [№509 "Про затвердження Порядку використання Державної геодезичної референцної системи координат УСК-2000 при здійсненні робіт із землеустрою"](http://zakon3.rada.gov.ua/laws/show/z1646-16), роботи із землеустрою мають виконуватись в системі координат УСК-2000 або місцевих системах координат, однозначно зв'язаних з системою координат УСК-2000.

Використовуючи значення параметрів, що наведенні у наказі [№509](http://zakon3.rada.gov.ua/laws/show/z1646-16) і паспортах [Державної геодезичної референцної системи координат УСК-2000](http://dgm.gki.com.ua/pasporti-derjavnoii-geodezichnoii-referencnoii-sistemi-coordinates-usk-2000) та [регіональних (місцевих) систем координат УСК-2000](http://dgm.gki.com.ua/pasporti-regionalnih-systems-coordinates-usk-2000), було створено датум і проекції УСК-2000 для роботи з ПЗ TopSURV, TopconTools та Magnet Field/Office. Параметри трансформації в файлі датуму визначено для перетворення ETRS89/ETRF2000->ITRS/ITRF2000->УСК-2000 (епоха 2005.0).

Для використання розпакуйте вміст архіву в відповідні папки зазначеного програмного забезпечення. 

При роботі в режимі RTK від мережі [TNT-TPI GNSS Network](https://net.tnt-tpi.com) використовуйте точку монтування TNT_2000_RTCM3.

**Важливо!** Не викорстовуйте наведені параметри для трансформації СК42/63 <-> УСК-2000! Для цього потрібно користуватись [Геодезичним калькулятором](http://dgm.gki.com.ua/ua/transkord).

##Перелік регіональних (місцевих) систем координат

|Територія покриття|Повна назва системи координат|Ідентифікатор системи координат|
|------------------|-----------------------------|-------------------------------|
|м. Київ|Місцева система координат м. Київ – УСК-2000|МСК-80|
м. Севастополь|Місцева система координат м. Севастополь – УСК-2000|МСК-85
Автономна Республіка Крим|Місцева система координат АР Крим – УСК-2000|МСК-01
Вінницька область|Місцева система координат Вінницької області – УСК-2000|МСК-05
Волинська область|Місцева система координат Волинської області – УСК-2000|МСК-07
Дніпропетровська область|Місцева система координат Дніпропетровської області – УСК-2000|МСК-12
Донецька область|Місцева система координат Донецької області – УСК-2000|МСК-14
Житомирська область|Місцева система координат Житомирської області – УСК-2000|МСК-18
Закарпатська область|Місцева система координат Закарпатської області – УСК-2000|МСК-21
Запорізька область|Місцева система координат Запорізької області – УСК-2000|МСК-23
Івано-Франківська область|Місцева система координат Івано-Франківської області – УСК-2000|МСК-26
Київська область|Місцева система координат Київської області – УСК-2000|МСК-32
Кіровоградська область|Місцева система координат Кіровоградської області – УСК-2000|МСК-35
Луганська область|Місцева система координат Луганської області – УСК-2000|МСК-44
Львівська область|Місцева система координат Львівської області – УСК-2000|МСК-46
Миколаївська область|Місцева система координат Миколаївської області – УСК-2000|МСК-48
Одеська область|Місцева система координат Одеської області – УСК-2000|МСК-51
Полтавська область|Місцева система координат Полтавської області – УСК-2000|МСК-53
Рівненська область|Місцева система координат Рівненської області – УСК-2000|МСК-56
Сумська область|Місцева система координат Сумської області – УСК-2000|МСК-59
Тернопільська область|Місцева система координат Тернопільської області – УСК-2000|МСК-61
Харківська область|Місцева система координат Харківської області – УСК-2000|МСК-63
Херсонська область|Місцева система координат Херсонської області – УСК-2000|МСК-65
Хмельницька область|Місцева система координат Хмельницької області – УСК-2000|МСК-68
Черкаська область|Місцева система координат Черкаської області – УСК-2000|МСК-71
Чернівецька область|Місцева система координат Чернівецької області – УСК-2000|МСК-73
Чернігівська область|Місцева система координат Чернігівської області – УСК-2000|МСК-74

##Історія змін:

[2013.01.30] УСК-2000 3 та 6-ти градусні зони.

[2017.01.15] Додано МСК-80, 81, 85, 01, 05, 07, 12, 14, 18, 21, 23, 26.

[2017.01.17] Додано всі регіональні системи координат.
