> Сколько Силы может произвести Йода?
>
> — Ryan Finnie

![Йода контролирующий ветряные генераторы](/uploads/yoda/01.png)

Я конечно буду игнорировать приквелы.

Есть отличный [комикс SMBC](http://www.smbc-comics.com/index.php?db=comics&id=2305#comic) показывающий геополитические последствия того, что Супермен будет вращать ручку, предоставляя неограниченный источник энергии. Мы можем представить Йоду использующего Силу для того, чтобы заставлять работать генератор. Но насколько много энергии он сможет произвести?

Самым лучшим проявлением силы Йоды в оригинальной трилогии был подъём X-Wing Люка из болота. Судя по всему, физическое перемещение объёктов, это самое энергоёмкое употребление Силы из всех, что можно найти в трилогии.

Энергия необходимая для того чтобы поднять объект на высоту h пропорциональна массе объекта, умноженного на ускорение свободного падения, умноженного на высоту подъёма. Сцена с подъёмом X-Wing позволяет нам увидеть нижний предел выходной мощности Йоды.

Сперва нам нужно понять, насколько тяжёл был корабль. Масса X-Wing никогда не была однозначно установлена, но его длина - 12.5 метров. Истребитель F-22 19 метров длиной и весит 19700 кг, таким образом пропорциональное уменьшение даёт нам вес X-Wing что-то около 12 000 фунтов (5 метрических тонн).

![Иллюстрация с X-Wing и F-22](/uploads/yoda/02.png)

$ m_{x} = m_{f22} * \left(\frac{12.5}{19}\right)^{3} \! \approx \, 5,600\mathrm{kg} $

Далее нам необходимо знать, насколько быстрым был подъём. Я внимательно просмотрел сцену и замерил скорость подъёма X-Wing из воды.

![персонаж смотрит Star Wars для научных исследований](/uploads/yoda/04.png)

Передняя стойка появляется из воды примерно через три с половиной секунды, я предположил, что её длина примерно равна 1.4 метра (основано на сцене в эпизоде "Новая надежда", где член экипажа висел на нём), что говорит нам о том, что X-Wing поднимался со скоростью 0,39 м/с.

И в конце концов нам нужно знать, какая сила гравитации была на планете Дагоба. Я думал, что я застрял, потому что хоть фанаты sci-fi хоть и помешаны на этом, но вряд ли существует каталог геофизических параметров на каждую планету посещённую в Звёздных войнах. Правильно?

Ничего подобного. Я недооценил сообщество. Вукипедия имеет такой каталог и там написано, что ускорение свободного падения на Дагобе 0.9g. Соединяя это с массой X-Wing и скоростью подъёма мы получим пиковую выходную мощность:

$ \frac{5,600 \mathrm{kg} \times 0.9\mathrm{g} \times 1.4 \text{ meters}}{3.6 \text{ seconds}} = 19.2\mathrm{kW} $

Этой энергии достаточно чтобы питать несколько пригородных домов. Также это эквивалентно 25 лошадиным силам, что является сравнимым с мощностью Smart с электрическим мотором.

![Йода в моторном отделении Смарта](/uploads/yoda/06.png)

По текущим ценам на электричество, стоимость энергии производимой Йодой будет около 2$ в час.

Но телекинез это только один тип Силы. Что насчёт молний, которыми Император бил Люка? Физическая природа Силы никогда не будет объяснена, но трансформаторы Тесла которые производят [похожие молнии](http://www.youtube.com/watch?v=uNJjnz-GdlE) выдают что-то около 10 [киловатт](http://www.goodchildengineering.net/tesla-coils/drsstc-5-10kw-monster), что поставит энергоэффективность Императора наравне с Йодой. (Трансформатор Тесла производит много коротких импульсов тока. Если Император будет поддерживать электрическую дугу постоянно, как например в дуговом сварочном аппарате, то мощность легко перевалит за мегаватты.)

А что насчёт Люка? Я просмотрел сцену, где он использует свою Силу впервые, чтобы вытащить свой световой меч из снега. Привести цифры расчёта будет непросто, но я просмотрел сцену покадрово и пришёл к выводу, что пиковая выходная мощность составляет около 400 ватт. Это лишь малая часть выхода Йоды, но и заняло это доли секунды.

Таким образом, Йода становится лучшим энергетическим источником. Но мировой уровень потребления достигает двух тераватт и потребуется сто миллионов Йод, чтобы удовлетворить наши потребности. И из-за этого переход на Силу Йоды будет невыгодным, хотя она будет в буквальном смысле "зелёной".

![Йода слушающий MP3 плеер и контролирующий его при помощи Силы](/uploads/yoda/yoda_07.png)

[Оригинал](http://what-if.xkcd.com/3/)

### Комментарии

1. [SMBC](http://www.smbc-comics.com/) - сайт с комиксами, на мой взгляд почти такие же смешные, как и комиксы [xkcd](http://xkcd.com/) или [Cyanide and Happiness](http://www.explosm.net/comics).
2. 1 фунт - 453.59 грамма, метрическая тонна - 1000 кг (есть ещё другие тонны и в терминах автора это не очень очевидно, что именно он имеет ввиду).
3. Йода на последней картинке не подключен к устройству в качестве источника питания, как можно подумать, а слушает музыку :)