# Индекс Шаурмы
*шуточный проект по сравнению уровня жизни в регионах страны, сделан командой на http://msk.opendataday.ru*

![](https://static.tildacdn.com/tild6564-6130-4734-b263-343436383930/p_o_reqDeCM.jpg)

Существует Индекс Бигмака, который анализирует адекватность курса валют из предположения, что во всех странах на одни и те же 50$ в местной валюте должно быть куплено одно и то же количество бигмаков. Если в одной стране их можно купить в 2 раза меньше, чем в другой - это трактуется как значительная недооценённость курса первой страны.

Однако, этот индекс не учитывает, сколько люди действительно могут тратить денег на бургеры и прочие радости жизни. Так, если всю зарплату занимает еда и съём квартиры - то хотелось бы, чтобы индекс был равен 0. Если свободных денег даже не хватает - чтобы индекс был меньше 0. И хотелось бы, чтобы новый индекс был легко трактуем. Поэтому рассчитаем новый индекс.

Рассчитаем Индекс Шаурмы как количество шаверм в день, на которые хватает оставшихся после обязательных расходов денег. А конкретнее:

**(средняя з/п - прожиточный минимум - аренда однокомнатной квартиры) / цена шаурмы / 30 дней**

## Результаты:

### Индекс Шаурмы

Например, жители Ямало-Ненецкого АО могут позволить себе почти 11 шаверм в день!
А жителям Новосибирской области не хватает даже на одну

![Индекс шаурмы](https://static.tildacdn.com/tild6431-3836-4434-b461-376239393933/noroot.jpg)
[*Интерактивная карта*](https://public.tableau.com/profile/vladislav5690#!/vizhome/_9688/Dashboard1)

#### Распределение Индекса Шаурмы

В среднем, свободных денег жителей России хватает на 2-3 шавермы в день, и в большинстве регионов значения близки к этому среднему. Однако, можно увидеть 5 субъектов, которым не хватает денег даже на одну, и 3 субъекта, которые могут себе позволить 10 шаверм в день. Москва с её дорогой арендой оказывается здесь только на седьмом месте с результатом 7 шаверм в день

![Распределение Индекса Шаурмы](https://static.tildacdn.com/tild6138-3464-4932-a233-396130323365/index.png)

#### Лидеры
Ямало-Ненецкий АО, Ханты-Мансийский АО, Ненецкий АО, Тюменская область, Магаданская область

#### Анти-лидеры
Севастополь, Крым, Новосибирская область, Республика Дагестан, Кемеровская область


### Цена шаурмы в регионах России

![Цена шаурмы в регионах России](https://static.tildacdn.com/tild3634-3036-4966-b861-626366623233/noroot.jpg)
[*Интерактивная карта*](https://public.tableau.com/profile/vladislav5690#!/vizhome/_9688/Dashboard1)


#### Распределение цен на шаурму

Максимальная цена отличается от минимальной в 2 раза, 190р против 80р. Есть явный тренд на более дешёвую шаурму на юго-западе и значительно более дорогую на севере. Впрочем, не без исключений. В среднем, шаурма стоит 121 рубль

![Распределение цен на шаурму](https://static.tildacdn.com/tild3264-3839-4366-b965-333137636537/price.png)



## Источники
**Средняя заработная плата и прожиточный минимум:**

Росстат


**Средняя стоимость квартир по регионам:**

ЦИАН, по каждому региону с сайта собрано по 2000 объявлений о аренде однокомнатных квартир, вычислена медианная по региону цена аренды 1 квадратного метра, умножена на единый метраж: 28 квадратных метров


**Стоимость шаурмы:**

Ручной сбор данных из групп vk.com и от региональных друзей участников команды
