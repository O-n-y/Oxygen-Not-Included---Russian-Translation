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
* Priniting Pod - Биопринтер
* Building - Постройка
* Neutronium - Нейтрониум
* Power - Электричество
* Tile - Блок
* Wire - Провод
* Insulation - Теплоизоляция
* Entombed - Завалено
* Fleeing - Убегает
* Idle - Бездействует
* Building - Постройка
* Sweep - Убрать
* Deliver - Доставка
* Transporting - Транспортирует
* Insulated Tile - Теплоизоляционный блок
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

# Животный мир, Растения, Еда
* Meal Lice - Мукоед
* Mealwood - Мучное дерево
* Muckroot - Гнилькорень
* Sleet Wheat - Морозная пшеница
* Sleet Wheat Grain - Зерно морозной пшеницы
* Peppernut - Перечный орех
* Pincha Pepperplant- Пинча перечная
* Thimble Reed - Прядун
* Wheezewort - Хладодых
* Swamp Lily - Болотная Лилия
* Muckroot - Гнилькорень
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
* Plug Slug - Плюгл
* Smog Slug - Смогул
* Sponge Slug - Губул
* Beeta - Биита
* Bliss Burst - Радоцвет
* Alveo Vera - Альвеух
* Bog Bucket - Багровник
* Dasha Salt Vine - Сольдавица
* Grubgrub - Грызогрыз
* Sweetle - Сладкополз
* Brackwax - Браковакс
* Sherberry - Морозник
* Pikeapple - Колючебус
* Plume Squash - Плюмовая тыква
* Spigot Seal - Сифонник
* Grubfruit- Корнефрут
* Tranquil Toes - Тихоцвет
* Bonbon Tree - Дерево Бонери
* Idylla - Мечтокрас
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
* Tonic Root - Тонизирующий корень


## Условия использования перевода
Перевод запрещено использовать с целью внесения изменений и\или распространения, в том числе под своим именем. 
Перевод разрешен и предназначен для использования только в том виде, в котором он существует, в игре Oxygen Not Included. 
## Usage permissions and limitations
Translation not allowed to use for editing or/and publishing under third-party name, fully or partly.
Translation permitted and made to be used only in existing form in the game Oxygen Not Included.
