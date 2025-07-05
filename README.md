# Oxygen-Not-Included---Russian-Translation

Русская локализация для игры "Oxygen Not Included"

Информация о переводе в Steam: http://steamcommunity.com/sharedfiles/filedetails/?id=874932276

*100% перевод, включающий исходный релиз Frosty Planet Pack и Spaced Out DLC*
В процессе обновления перевода до патча 622372

![100% перевод, включающий Frosty Planet Pack и Spaced Out DLC](https://raw.githubusercontent.com/O-n-y/oxy.mods/master/oxy_supporred.png)

# Автор перевода и как связаться (Steam):
* Ony: http://steamcommunity.com/id/oniki/

# Из Воркшопа Стим
Подписаться на мод: http://steamcommunity.com/sharedfiles/filedetails/?id=927642162
В настройках игры -> Options -> Choose a different language - выбрать там русскую локализацию
Стим воркшоп работает, но с глюком, чтобы увидеть локализацию, после подписки нужно выйти из меню и зайти туда еще раз, там появится локализация - 2 раза кликните на ней, она подгрузится. 
+ После этого клиент перезапустить :)

# Скачать последнюю версию
*Это упрощенный вариант, рекомендуется использовать github desktop или консоль гита для оперативного получения обновлений.*
Скачать: https://github.com/O-n-y/Oxygen-Not-Included---Russian-Translation/archive/master.zip

# Стадия перевода

На данный момент первичный перевод закончен. Текущая стадия - вычитка и правка.
+ Постоянные дополнения по ходу выхода новых патчей и DLC.
Если Вы хотите в ней участвовать - делайте пул реквесты. Старайтесь делать их небольшими порциями, чтобы пул реквест с большей вероятностью был слит с основной веткой. 
Чем больший объем пул реквеста, тем больше он потребует обсуждений и тем с большей вероятностью будет отвергнут - чтобы он был слит, необходимо чтобы все правки были приняты и подтверждены ответственными людьми.
Не берите на себя ответственность переводчика \ корректировщика, если не уверены, что владеете русским \ английским языками на достаточном уровне или если не играли достаточное время в игру (необходимо понимать нюансы контекста).

# Переводчикам и корректорам

## Как принять участие в переводе \ корректировке
* Заведите аккаунт на github, активируйте его - подтвердите емайл
* Сделайте Fork - проекта (кнопка справа вверху)
* Откройте форкнутый проект (этот проект под Вашим аккаунтом - копия)
* Поставьте программу https://desktop.github.com/
* После того, как программа установлена и запущена: На странице форкнутого проекта нажмите "Clone or Download" -> Open in Desktop
* Проект склонируется Вам на жесткий диск

## Начало работы и Push изменений
* Перед началом внесения очередных изменений всегда синхронизируйтесь (Sync в правом верхнем углу Github Desktop)
* Внесите изменения в файл strings.pot
* Откройте Github Desktop, убедитесь что выбрана ветка master (это ваша форкнутая копия основного проекта)
* Вкладка "Changes" - будет содержать список ваших изменений
* В "Summary" укажите номера измененных строк, например: 1000-2000
* Нажмите "Commit to master"
* Синхронизируйтесь (Sync в правом верхнем углу Github Desktop)
* Нажмите "Pull request" (правый верхний угол  Github Desktop)
* Убедитесь что выбран пул из master в Ony master
* В "Summary" укажите номера измененных строк, например: 1000-2000
* Нажмите "Send pull request"
* Синхронизируйтесь (Sync в правом верхнем углу Github Desktop)

## Внесение изменений и Merge в основную ветку
* После того как вы отправили Push в основную ветку, вы можете увидеть его в списке pull requests: 
https://github.com/O-n-y/Oxygen-Not-Included---Russian-Translation/pulls
* Он будет рассмотрен администратором и при необходимости скорректирован, после чего слит в основную ветку или же отклонен с комментарием, содержащим причину.

# В разное время помогали переводу
Ony, Cores, ShaTiK, SealOfTheTime, henko, Dr. RPgK, pecypc, OsiWops, mmalinin, strategdzr, dmtazetdinov 


# Инструкции по файлу перевода (от разработчиков Oxygen Not Included)

## Создание файла перевода

    Откройте папку игры "Oxygen Not Included" через правый клик мышки в свойствах игры в библиотеке Steam, перейдите в локальные файлы и откройте их.
	Откройте папку "Mods", которая расположена по пути "OxygenNotIncluded_Data/StreamingAssets/Mods"
	Скопируйте "strings.po" файл.
	Заполните строки между "" с названием "msgstr"

Примечание: не нужно переводить любые слова в таких скобках {} или таких <>, потому что они используются игрой.


## Использование файла перевода

	Загрузите файл перевода "strings.po".
	Откройте папку игры "Oxygen Not Included" через правый клик мышки в свойствах игры в библиотеке Steam, перейдите в локальные файлы и откройте их.
	Откройте папку "Mods", которая расположена по пути "OxygenNotIncluded_Data/StreamingAssets/Mods"
	Скопируйте полученный "strings.po" файл в эту папку.


# Базовые понятия
* Duplicant - Дупликант (всегда пишется с заглавной буквы)
* Printing Pod - Биопринтер
* Building - Постройка
* Neutronium - Нейтрониум
* Power - Электричество
* Tile - Блок
* Wire - Провод
* Insulation - Теплоизоляция
* Entombed - Завалено
* Fleeing - Убегает
* Idle - Бездействует
* Sweep - Убрать
* Deliver - Доставка
* Transporting - Транспортирует
* Disease - Болезнь
* Skill \ Attribute - Навык \ Характеристика
* Liquid Pipes - Водопроводные трубы
* Liquid Pipe - Водопроводная труба
* Novice Research - Базовое Исследование
* Storage - Хранилище
* Storage Bin - Склад
* Generator - Генератор
* Hatchery - Инкубатор
* Research Lab - Лаборатория исследований
* Automation - Автоматизация
* Sensor - Датчик
* Maintenance - Техническое обслуживание
* Solid Materials - Твердотелые ресурсы
* Rocket - Шаттл
* Rocket Platform - Платформа для шаттлов
* Critter Cargo Bay - Отсек для существ
* Spice Grinder - Измельчитель специй
* Super Coolant - Супер-хладагент
* Fullerene - Фуллерен
* Ooze - Ил
* Radbolt - Радчастица
* Exosuit - Экзокостюм
* Errand - Задача
* Skill - Навык
* Tier - Уровень
* Tune Up - Подстройка
* Vent - Расщелина

## Ресурсы и материалы
* Bleach Stone - Хлорная известь
* Polluted Dirt - Загрязненная земля
* Enriched Uranium - Обогащенный уран
* Brackwax - Браковакс
* Sucrose - Сахароза
* Plastium - Пластиум
* Thermium - Термиум
* Visco-Gel - Виско гель
* Yellowcake - Желтый кек
* Insulite - Изоляция
* Rust - Ржавчина
* Oxylite - Оксилит
* Fertilizer - Удобрение
* Petroleum - Керосин
* Fossil - Ископаемое
* Dream Journal - Дневник Сновидений
* Brackene - Бракен
* Reed Fiber - Тростниковое волокно
* Tonic Root - Тонизирующий корень
* Wood - Древесина
* Lime - Известняк
* Genetic Ooze - Генетический ил
* Brine - Рапа
* Brine Ice - Раповый лед
* Slime - Слизь
* Isoresin - Изо-смола
* Liquid Resin - Смола
* Corium - Кориум
* Abyssalite - Абиссалит
* Nuclear Fallout - Ядерные отходы

## Постройки и объекты
* Neural Vacillator - Нейронный подстройщик
* Farm Station - Станция подкормки
* Farm Tile - Блок-ферма
* Insulated Tile - Теплоизоляционный блок
* Fertilizer Synthesizer - Синтезатор удобрений
* Fish Release - Освободитель рыбок
* Fish Feeder - Кормушка для рыбок
* Fish Trap - Ловушка для рыбок
* Weight Plate - Прижимная плита
* Hydroponic Farm - Гидропонная ферма
* Ice Maker - Ледогенератор
* Manual Airlock - Ручной шлюз
* Metal Refinery - Очиститель руды
* Microbe Musher - Миксер микробов
* Oil Refinery - Нефтеперегонная установка
* Ore Scrubber - Обеззараживатель руды
* Outhouse - Отхожее место
* Power Shutoff - Электро контроллер
* Research Reactor - Научный реактор
* Triage Cot - Мед. кровать
* Carbon Skimmer - Скиммер углерода
* Electrolyzer - Электролизер
* Desalinator - Опреснитель
* Thermo Regulator - Терморегулятор
* Algae Terrarium - Террариум водорослей
* Duplicant Checkpoint - Контрольная точка Дупликанта
* Critter Trap - Ловушка для существ
* Airborne Critter Trap - Ловушка для летающих существ
* Algae Distiller - Биодистиллятор
* Atmo Suit - Экзокостюм
* Interplanetary Launcher - Межпланетная пусковая установка
* Payload Opener - Распаковщик грузов
* Grooming Station - Груминг-Станция
* Ration Box - Коробка для еды
* Mechanized Airlock - Авто шлюз
* Conveyor Rail - Конвейерный рельс
* Conveyor Loader - Конвейерный загрузчик
* Conveyor Receptacle - Конвейерный разгрузчик
* Conveyor Meter - Конвейерный счетчик
* Conveyor Shutoff - Выключатель конвейера
* Auto-Sweeper - Хватальщик
* Launch Toggle - Переключатель запуска
* Rocket Cockpit - Кабина шаттла
* Rocket Control Station - Центр управления шаттлом
* Cargo Bay - Грузовой отсек
* Biological Cargo Bay - Биологический грузовой отсек
* Trailblazer Module - Модуль Первопроходца
* Rover's Module - Модуль Скаут
* Steam Engine - Паровой двигатель
* Sugar Engine - Сахарный двигатель
* Power Outlet Fitting - Розетка
* Transit Tube - Транзитная труба
* Transit Tube Access - Точка доступа к транзитной системе
* Supply Teleporter - Телепортер снабжения
* Molecular Forge - Молекулярный расщепитель
* Skill Scrubber - Перераспределитель навыков
* Jet Suit Dock - Док-станция реактивных костюмов
* Lead Suit Dock - Док антирадиационных костюмов
* Geotuner - Геотюнер
* Somnium Synthesizer - Синтезатор Сомний
* Biobot Builder - Фабрика биороботов
* Orbital Data Collection Lab - Орбитальная лаборатория
* Pajama Cubby - Шкафчик для пижам
* Botanical Analyzer - Ботанический анализатор
* Materials Study Terminal - Терминал материй
* Acoustic Art Panel - Акустическая художественная панель
* Coat Rack - Вешалка для одежды
* Murphy Bed - Кровать-Мерфи
* Reception Desk - Ресепшен
* Water Cooler - Кулер
* Water Fort - Подводный домик
* Wire Bridge - Провод-мост
* Heavi-Watt Joint Plate - Соединительная пластина
* Conductive Wire - Провод II
* Conductive Wire Bridge - Провод-мост II
* Heavi-Watt Conductive Joint Plate - Соединительная пластина II
* Heavi-Watt Conductive Wire - Плотный провод II
* Power Control Station - Станция управления мощностью
* Power Transformer - Маленький трансформатор
* Large Power Transformer - Трансформатор
* Switch - Рубильник
* Tempshift Plate - Термо-плита
* Storage Tile - Блок-склад
* Wall Toilet - Туалет-перегородка
* Wash Basin - Умывальник
* Sublimation Station - Станция сублимации
* Soda Fountain - Фонтанчик с содовой
* Solar Panel - Солнечная панель
* Space Heater - Обогреватель
* Rust Deoxidizer - Раскислитель ржавчины
* Sludge Press - Грязевой пресс
* Exosuit Forge - Цех экзокостюмов
* Atmo Suit Dock - Док экзокостюмов
* Atmo Suit Checkpoint - Контрольная точка экзокостюмов
* Telescope - Телескоп
* Rock Crusher - Измельчитель минералов
* Teleporter Pad - Площадка телепорта
* Planter Box - Ящик для рассады
* Shearing Station - Станция подстрижки
* Research Station - Станция науки
* Research Module - Научный модуль
* Uranium Centrifuge - Урановая центрифуга
* Sweepy's Dock - Док Свиппи
* Temporal Tear Opener - Временной портал
* Temporal Bow - Временной Лук
* Geo Vent - Геовент
* Critter Condo - Гнездо для существ
* Sick Bay - Лазарет
* Disease Clinic - Клиника болезней
* Mess Table - Столовая
* Command Capsule - Командный модуль
* Electric Grill - Электрогриль
* Super Computer - СуперЭВМ
* Hospital - Больничный отсек
* Nature Reserve - Заповедник
* Massage Clinic - Массажная комната
* Mission Control Station - Станция управления полетами

## Растения, животные и еда
* Meal Lice - Мукоед
* Mealwood - Мучное дерево
* Muckroot - Гнилькорень
* Sleet Wheat - Морозная пшеница
* Sleet Wheat Grain - Зерно морозной пшеницы
* Peppernut - Перечный орех
* Pincha Pepperplant - Пинча перечная
* Thimble Reed - Прядун
* Wheezewort - Хладодых
* Swamp Lily - Болотная Лилия
* Palmera Tree - Дерево Пальмера
* Bristle Blossom - Щитовик Цветущий
* Bristle Briar - Шиповник
* Mush bar - Мшистый батончик
* Bristle Berry - Щетинистая ягодка
* Stuffed Berry - Фаршированная ягодка
* Gristle Berry - Хрустящая Ягодка
* Frost Bun - Ледяная булочка
* Liceloaf - Батончик из мукоедов
* Mealwood Sap - Сок мучного дерева
* Muckroot Juice - Сок гнилкокорня
* Bristle Blossom Nectar - Нектар щитовика цветущего
* Swamp Lily Bulb - Луковица болотной лилии
* Peppernut Oil - Масло из перечного ореха
* Plug Slug - Плюг
* Smog Slug - Смогул
* Sponge Slug - Губул
* Beeta - Биита
* Bliss Burst - Радоцвет
* Alveo Vera - Альвеух
* Bog Bucket - Багровник
* Dasha Salt Vine - Сольдавица
* Grubgrub - Грызогрыз
* Sweetle - Сладкополз
* Sherberry - Морозник
* Pikeapple - Колючебус
* Plume Squash - Плюмовая тыква
* Spigot Seal - Сифонник
* Grubfruit - Корнефрут
* Tranquil Toes - Тихоцвет
* Bonbon Tree - Дерево Бонери
* Idylla Flower - Мечтокрас
* Hydrocactus - Аквалючка
* Saturn Critter Trap - Сатурнянка
* Lumen Quartz - Люменовый кварц
* Shove Vole - Космолевка
* Delecta Vole - Дэлектолевка
* Bammoth - Баммут
* Sanishell - Мокребс
* Pokeshell - Кребс
* Oakshell - Дубокребс
* Pip - Пип
* Cuddle Pip - Мягкопип
* Balm Lily - Бальзамная лилия
* Sporechid - Злоцвет
* Nosh Bean - Боб ноша
* Jumping Joya - Прыгающий радостин
* Hexalent - Гексалент
* Hatch - Норник
* Morb - Морб
* Puft - Пуфт
* Pacu - Паку
* Gulp Fish - Рыбка-глотальщик
* Gassy Moo - Газомус
* Flox - Флокс
* Divergent - Дивергент
* Drecko - Дрэко
* Gas Grass - Газовая трава
* Bluff Briar - Шиповник-обманщик
* Arbor Tree - Дерево Арбора
* Sporb - Спорб
* Mellow Mallow - Мальва
* Mirth Leaf - Мирта
* Abyss Bug - Анти-светлячок
* Azure Bug - Лазурный светлячок
* Royal Bug - Королевский светлячок
* Sage Hatch - Шалфейный норник
* Smooth Hatch - Гладкий норник
* Stone Hatch - Каменный норник
* Squeaky Puft - Пуф-скрипун
* Puft Prince - Пуф-принц
* Sun Bug - Солнечный светлячок
* Coral Bug - Коралловый светлячок
* Waterweed - Элодея
* Swamp Chard - Багровник
* Balm Lily Flower - Цветок бальзамной лилии
* Spindly Grubfruit Plant - Куст Корнефрута
* Critter - Существо
* Mutant Seeds - Мутированные семена

## Шаттлы и космос
* Rocket Module - Модуль шаттла
* Carbon Dioxide Engine - Двигатель на углекислом газе
* Battery Module - Аккумуляторный модуль
* Artifact Transport Module - Модуль транспортировки артефактов
* Virtual Planetarium - Планетарий
* Cartographic Module - Картографический модуль
* Sight-Seeing Module - Туристический модуль
* Solar Panel Module - Модуль солнечной панели
* Solid Fuel Thruster - Твердотопливный двигатель
* Spacefarer Module - Жилой модуль шаттла
* Temporal Tear - Червоточина
* Rocket Navigation - Навигация в космосе
* Rocket Piloting - Пилотирование шаттла
* Space Mission - Космическая миссия
* Planetoid - Планетоид
* Drillcone - Носовой бур

## Исследования и навыки
* Field Research - Географический анализ
* Applied Sciences Research - Атомная физика
* Crop Tending - Уход за растениями
* Mechatronics Engineering - Мехатроника
* Oil Engineering - Нефтяная инженерия
* Pyrotechnics - Пиротехника
* Art Fundamentals - Основы искусства
* Masterworks - Пространственное восприятие
* Aesthetic Design - Эстетический дизайн
* Hard Digging - Копание твердых пород
* Superhard Digging - Копание абиссалита
* Hazmat Digging - Копание опасных пород
* Improved Construction I - Базовое строительство
* Improved Construction II - Ускоренное строительство
* Demolition - Демонтаж
* Plumbing - Прочистка труб
* Grilling - Искусство гриля
* Medicine Compounding - Производство лекарств
* Bedside Manner - Лечение Дупликантов
* Advanced Medical Care - Улучшенная медицинская забота
* Improved Farming I - Фермерство
* Improved Farming II - Улучшенное фермерство
* Improved Carrying I - Базовая переноска
* Improved Carrying II - Улучшенная переноска
* Improved Tinkering - Улучшенная механика
* Electrical Engineering - Работа с электричеством
* Astronomy - Астроном
* Exosuit Training - Экзокостюмы
* Data Analysis Research - Астрономические исследования
* Materials Science Research - Исследования материй
* Genetic Analysis - Генетический анализ

## Персонажи и локации
* Director Stern - Директор Стерн
* Dr. Broussard - Доктор Бруссар
* The Gravitas Facility - Центр Гравитас
* Ceres - Церера
* Cluster - Кластер
* Terrania Cluster - Песчаный кластер
* Quagmiris Cluster - Трясинный кластер
* The Badlands Cluster - Кластер Диких Земель
* Rime Cluster - Ледяной Кластер
* Squelchy Cluster - Хлюпающий Кластер
* Oily Swamp Asteroid - Астероид маслянистых болот

## Эффекты/состояния
* Banshee Wail - Вопль Баньши
* Stress Vomit - Рвота на почве стресса
* Ugly Cry - Страшный плач
* Floral Scent - Цветочная пыльца
* Trench Stench - Гнилостный запах
* Zombie Spores - Зомбоспоры
* Sunburn - Солнечный ожог
* Radiation Sickness - Лучевая болезнь
* Slimelung - Слизь в легких
* Allergic Reaction - Аллергическая реакция
* Food Poisoning - Пищевое отравление
* Narcoleptic Nap - Нарколептический сон
* Overjoyed - Переполнение от счастья
* Sticker Bomb - Бомба из стикеров

## Одежда/Снаряжение
* Jet Suit - Реактивный костюм
* Lead Suit - Антирадиационный костюм
* Thermo Suit - Термокостюм
* Oxygen Mask - Кислородная маска
* Oxygen Tank - Кислородный баллон
* Oxygen Rebreather - Дыхательный аппарат
* Cool Vest - Охлаждающий жилет
* Warm Coat - Теплый свитер
* Pajamas - Пижамы
* Snazzy Suit - Стильный костюм
* Aqua Suit - Аквакостюм
* Atmo Belt - Экзоремень

## Черты характера
* Balloon Artist - Художник по шарам
* Narcoleptic - Нарколепсия
* Squeamish - Брезгливый
* Iron Gut - Стальные кишки
* Small Bladder - Маленький мочевой пузырь
* Loud Sleeper - Храпун
* Claustrophobic - Клаустрофобия
* Vertigo Prone - Акрофоб
* Fashionista - Модник
* Pudgy - Толстокожий
* Skinny - Тонкокожий
* Delicate Feetsies - Деликатные стопы
* Solitary Sleeper - Сыч-одиночка
* Workaholic - Трудоголик
* Nyctophobic - Никтофобный
* Night Owl - Сова
* Noodle Arms - Лапшерукий
* Radiation Eater - Поедатель радиации
* Critter Aversion - Ненавистник существ
* Animal Lover - Любитель существ
* Regenerative - Регенерирующий
* Beefsteak - Крушитель
* Pacifist - Пацифист
* Shrivelled Tastebuds - Простые вкусы
* Slow Learner - Блаженный
* Sparkle Streaker - Блескунчик
* Starry Eyed - Глаза-звездочки
* Sticker Bomber - Стикерный бомбермен
* Vomiter - Тошнючка
* Buff - Силач
* Germ Resistant - Природный иммунитет
* Sunny Disposition - Солнечный настрой
* Super Productive - Супер продуктивный
* Duress to Impress - Мазохист
* Twinkletoes - Балерина
* Uncultured - Неотесанный
* Biohazardous - Дохляк
* Grease Monkey - Технарь
* Green Thumb - Натуралист
* Yodeler - Йодлер
* Loner - Одиночка
* Luddite - Луддит
* Rock Fan - Метеоритный фанат
* Mole Hands - Кроторукий
* Mouth Breather - Дышит ртом
* Interior Decorator - Перфекционист
* Irritable Bowel - Раздраженный кишечник


## Условия использования перевода
Перевод запрещено использовать с целью внесения изменений и\или распространения, в том числе под своим именем. 
Перевод разрешен и предназначен для использования только в том виде, в котором он существует, в игре Oxygen Not Included. 
## Usage permissions and limitations
Translation not allowed to use for editing or/and publishing under third-party name, fully or partly.
Translation permitted and made to be used only in existing form in the game Oxygen Not Included.
