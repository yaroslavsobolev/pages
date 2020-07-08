---
title: 'УИКи-близнецы с разницей ровно в тысячу родинок'
subtitle: 'Некоторые избирательные участки (УИК) находятся в одном и том же доме, поэтому следовало бы ожидать от них 
одинаковых результатов голосования — это "участки-близнецы". Однако в 61 случае участки-близнецы отличаются 
друг от друга ровнёхонько на тысячу голосов "да" в итоговых протоколах общенародного голосования по поправкам в 
Конституцию.'
date: 2018-06-30 00:00:00
description: This page is a demo that shows everything you can do inside portfolio and blog posts.
featured_image: '/images/vote_rigging_1/rick.png'
---

[//]: # ("Смотрите внимательно, внучата, как ваш дедуля сейчас заменит единичку на нолик и тем самым разрушит целую галактическую империю одним махом." — Рик Санчез)

## Ландшафт

Первого июля 2020 года прошло всероссийское "общенародное голосование" по поправкам в Конституцию РФ. Присутствие 
электоральных фальсификаций на этом голосовании [выявлено](https://www.golosinfo.org/articles/144477) 
многочисленными [свидетельствами](https://www.kartanarusheniy.org/2020-07-01/list) наблюдателей 
и независимых членов избирательных комиссий, но суммарный масштаб и уродливый лейтмотив этих фальсификаций в нагляднее
 всего демонстрируется простым статистическим анализом
  [официальных данных](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&root_a=772000004&vrn=100100163596966&region=0&global=true&type=0&sub_region=99&prver=0&pronetvd=null) 
с сайта Центральной Избирательной Комиссии (ЦИК)
 — логика и результаты 
 такого анализа были изложены Сергеем Шпилькиным
  [в его блоге](https://www.facebook.com/sergey.shpilkin/posts/3119490201472928),
   в [колонке Новой Газеты](https://novayagazeta.ru/articles/2020/07/02/86114-vot-i-vsya-lyubov) 
   и [комментарии Александра Киреева](https://novayagazeta.ru/articles/2020/07/06/86170-referendum-shredingera) 
   там же, а также в репортажах
[Forbes](https://www.forbes.ru/obshchestvo/404269-takogo-masshtaba-manipulyaciy-v-proshlom-ne-bylo-ekspert-zayavil-o-22-mln) 
и [BBC](https://www.bbc.com/russian/features-53271744). 
 Этот статистический анализ выгодно 
 отличается тем преимуществом, что для самостоятельной проверки его правильности читателю не требуется быть 
 экспертом в чём-либо: это под силу любому первокурснику технического вуза, да и просто 
 человеку, знакомому с программированием, а может быть и заметной части юзеров MS Excel. 
 Для такой проверки читателю достаточно скачать официальные данные с сайта ЦИК,
 проделать с этими данными те нехитрые вычисления, которые описывает Сергей Шпилькин, и взглянуть на 
 получившиеся графики. Я приведу аналогию: ксли вам кто-то заявляет, что `189841 + 97481 = 287322`, то вам не 
 обязательно погалаться на авторитет говорящего или требовать проверки этого утверждения "независимыми экспертами" — вы 
 можете собственноручно 
 сложить эти числа столбиком. Тем не менее, для тех читателей, кто полагается в таких вещах на "мнения 
 независимых 
 экспертов", в конце этого поста я прилагаю графики как в анализе Сергея Шпилькина, но воспроизведённые мной 
 собственноручно на данных ЦИК — никаких расхождений между моими графиками и его графиками я не заметил. Для 
 контекста, на [сайте Лаборатории Электоральной Статистики](https://www.electoral.graphics/ru-ru/) любой желающий 
 может интерактивно проделать аналогичный анализ официальных данных 
 прошедших выборов разных стран: Франции, Украины, России, Армении, Северной Македонии.

## Идея
Из всего разнообразия видов электоральных фальсификаций, замеченных во впечатляющих количествах на "общенародном 
голосовании", я сфокусируюсь в этом посте лишь на одной специальной их разновидности. Живой пример этого типа мухлежа —
следующая примечательная разница между итоговым протоколом, полученным членом избирательной 
комиссии №800 в Якутске (фото протокола — слева), и данными в 
официальной базе данных ЦИК (справа — скриншот вот
 [этой](http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=142000064&tvd=21420001011794&vrn=100100163596966&region=0&global=true&sub_region=99&prver=0&pronetvd=null&vibid=21420001011794&type=465) 
 страницы):
 
![](/pages/images/vote_rigging_1/uik800.jpg)

<sup>*Источник: [Твиттер](https://twitter.com/k_b_l_v/status/1279566757485637633) и 
["Новости Якутии"]((https://news.ykt.ru/article/103260?utm_source=tw&utm_medium=so&utm_campaign=izbirkom-yakutska-rasskazal-ob-oshibkah-v))*</sup>

Вглядитесь в отличающиеся цифры (помечено жёлтым): в базе данных (справа) цифра в разряде тысяч изменилась с нуля на 
единицу в графе "Да", с соответсвующим увеличением на тысячу в графах "Число бюллетеней, выданных участникам" и 
"Число бюллетеней, содержащихся в ящиках для голосования". Почему именно 
такой вид жульничества — с заменой 
одной цифры в разряде тысяч — излюблен 
фальсификаторами? Потому что в случае судебного разбирательства после выборов наш Самый Честный Суд в таких случаях 
всегда заключает, что произошла добросовестная описка ("техническая ошибка") — мол, "вместо нолика случайно написали
 единичку, с кем не бывает?" — и члены комиссии признаются невиновными. И точно: председатель 
 Территориальной Избирательной Комиссии (ТИК) Якутска
  Алла Самойлова 
[прокомментировала](https://news.ykt.ru/article/103260?utm_source=tw&utm_medium=so&utm_campaign=izbirkom-yakutska-rasskazal-ob-oshibkah-v) 
ситуацию именно в таком ключе: *"На 800-м участке участковый допустила ошибку <...> Ошибку заметило программное 
обеспечение <...> Люди 
  работали 
  целую неделю почти без отдыха, сказывается усталость"* 
  
 Давайте 
 подумаем, а 
 нельзя
  ли 
 путём анализа 
 данных выявить хотя бы часть тех избирательных участков страны, на которых провернули такой трюк? И тут нам приходит
  на 
 помощь 
 второй источник вдохновения — выполненная Денисом 
 Ольшиным [интерактивная визуализация](https://popravke.net/anomalies.html) официальных результатов голосования, в 
 которой каждый УИК изображён столбиком, чья высота показывает процент голосов "да" на этом УИКе. Серые рамочки 
 группируют столбики по их ТИКам. Столбики УИКов, сильно отличающихся по явке или результату от свои соседей, 
 окрашены красным или оранжевым для наглядности (подробные критерии окраски даны в описании на 
 [веб-странице](https://popravke.net/anomalies.html) этой визуализации). Вот небольшой фрагмент, показывающий 
 результаты Москвы и Хабаровского края:
 
![](/pages/images/vote_rigging_1/denis_1.png)

<sup>*Официальные результаты голосования 1 июля в Москве и Хабаровском крае, показанные в виде столбиков (по одному 
столбику на УИК), чья высота соответствует проценту голосов "да" на участке. Серыми рамками обведены УИКи одного 
ТИКа (то есть, географически близкие друг к другу). Автор визуализации: 
[Денис Ольшин](https://twitter.com/denullru/status/1279042332256620546). 
Посмотреть и потрогать эту визуализацию целиком — можно [здесь](https://popravke.net/anomalies.html).*</sup>
 
 
Такое отображение (его ещё называют 
["диаграммой Габдульвалеева"](https://www.electoral.graphics/ru-ru/laboratory/gab)) полезно для обнаружения УИКов, 
на которых число голосов "да" и/или явка разительно отличаются (иногда в два-три раза) от географически-соседних с 
ними УИКов. Такие аномальные выбросы (красные столбики на рисунке выше) 
[не наблюдаются](https://www.electoral.graphics/ru-ru/laboratory/gab) в 
исторических данных 
честных выборов в России (например, выборов мэра Москвы 2013) и в других странах (например, во 
[Франции](https://www.electoral.graphics/ru-ru/laboratory/gab)), и не имеют 
объяснения в каких-то причудах реального поведения избирателей. 
Здесь Вы можете возразить: "А что если все консервативные бабули района живут в одном квартале? Они-то и дают это 
различие". В 
ответ я попытаюсь найти среди этих соседей-УИКов, резко разнящихся по результату, не просто соседей по району, а 
соседей **по дому**: бывает, что по одному и тому же адресу находятся помещения для голосования сразу нескольких УИКов 
(всего я нашёл 8895 таких адресов, чаще всего это здание общеобразовательной школы). Согласитесь: было бы уж совсем 
необъяснимо, если бы избиратели, приходящие 
  голосовать в одно 
  и то же здание по
   месту жительства, голосовали бы совершенно по-разному в разных *комнатах* этого здания. Однако в официальных 
   данных ЦИК результаты на участках в одном и том же доме мало того что сильно отличаются между собой, так эта 
   разница в десятках случаев подозрительно похожа на ровно тысячу голосов "Да". Вот несколько найденных мной примеров:
   
## Улов
На этих 
графиках суммарная длина полоски каждого УИКа соответствует числу зарегистрированных избирателей (которое у УИКов 
неодинаково) сделана одинаковой для всех УИКов в одном доме, чтобы было удобнее сравнивать процентные соотношения. 
Оранжевая часть полоски (включая светло-оранжевую) это официальное число голосов "Да". Светло-оранжевая часть полоски — 
это уже я отметил последнюю тысячу официальных голосов "Да". Над рисунком подписан адрес помещения для голосования, 
под рисунком — ссылки на источник данных (соответствующуе страницы официального сайта ЦИК).

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/5883.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №408](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=332000022&tvd=23320001061886&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=23320001061886), [УИК №409](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=332000022&tvd=23320001061886&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=23320001061886)). Адрес и члены комиссий ([УИК №408](http://www.vladimir.vybory.izbirkom.ru/region/vladimir?action=ik&vrn=4334003192017), [УИК №409](http://www.vladimir.vybory.izbirkom.ru/region/vladimir?action=ik&vrn=4334003192018))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/5887.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №424](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=332000022&tvd=23320001061886&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=23320001061886), [УИК №425](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=332000022&tvd=23320001061886&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=23320001061886)). Адрес и члены комиссий ([УИК №424](http://www.vladimir.vybory.izbirkom.ru/region/vladimir?action=ik&vrn=4334003192033), [УИК №425](http://www.vladimir.vybory.izbirkom.ru/region/vladimir?action=ik&vrn=4334003192034))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/5901.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №402](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=332000022&tvd=23320001061886&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=23320001061886), [УИК №403](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=332000022&tvd=23320001061886&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=23320001061886)). Адрес и члены комиссий ([УИК №402](http://www.vladimir.vybory.izbirkom.ru/region/vladimir?action=ik&vrn=4334003192011), [УИК №403](http://www.vladimir.vybory.izbirkom.ru/region/vladimir?action=ik&vrn=4334003192012))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/6034.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №2562](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=522000020&tvd=25220001948854&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=25220001948854), [УИК №2563](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=522000020&tvd=25220001948854&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=25220001948854), [УИК №2564](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=522000020&tvd=25220001948854&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=25220001948854)). Адрес и члены комиссий ([УИК №2562](http://www.nnov.vybory.izbirkom.ru/region/nnov?action=ik&vrn=4524039210571), [УИК №2563](http://www.nnov.vybory.izbirkom.ru/region/nnov?action=ik&vrn=4524039210404), [УИК №2564](http://www.nnov.vybory.izbirkom.ru/region/nnov?action=ik&vrn=4524039210409))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/6083.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №2583](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=522000020&tvd=25220001948854&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=25220001948854), [УИК №2584](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=522000020&tvd=25220001948854&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=25220001948854), [УИК №2585](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=522000020&tvd=25220001948854&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=25220001948854)). Адрес и члены комиссий ([УИК №2583](http://www.nnov.vybory.izbirkom.ru/region/nnov?action=ik&vrn=4524039210524), [УИК №2584](http://www.nnov.vybory.izbirkom.ru/region/nnov?action=ik&vrn=4524039210528), [УИК №2585](http://www.nnov.vybory.izbirkom.ru/region/nnov?action=ik&vrn=4524039210533))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/84.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №1476](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=772000115&tvd=27720002420517&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27720002420517), [УИК №1477](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=772000115&tvd=27720002420517&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27720002420517), [УИК №1484](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=772000115&tvd=27720002420517&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27720002420517)). Адрес и члены комиссий ([УИК №1476](http://www.moscow_city.vybory.izbirkom.ru/region/moscow_city?action=ik&vrn=4774094258712), [УИК №1477](http://www.moscow_city.vybory.izbirkom.ru/region/moscow_city?action=ik&vrn=4774094259223), [УИК №1484](http://www.moscow_city.vybory.izbirkom.ru/region/moscow_city?action=ik&vrn=4774094260379))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/607.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №2759](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=772000021&tvd=27720002420423&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27720002420423), [УИК №2760](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=772000021&tvd=27720002420423&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27720002420423)). Адрес и члены комиссий ([УИК №2759](http://www.moscow_city.vybory.izbirkom.ru/region/moscow_city?action=ik&vrn=4774027165612), [УИК №2760](http://www.moscow_city.vybory.izbirkom.ru/region/moscow_city?action=ik&vrn=4774027165729))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/618.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №2792](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=772000006&tvd=27720002420408&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27720002420408), [УИК №2793](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=772000006&tvd=27720002420408&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27720002420408)). Адрес и члены комиссий ([УИК №2792](http://www.moscow_city.vybory.izbirkom.ru/region/moscow_city?action=ik&vrn=4774028156096), [УИК №2793](http://www.moscow_city.vybory.izbirkom.ru/region/moscow_city?action=ik&vrn=4774028156229))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/775.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №244](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=772000004&tvd=27720002420406&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27720002420406), [УИК №245](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=772000004&tvd=27720002420406&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27720002420406)). Адрес и члены комиссий ([УИК №244](http://www.moscow_city.vybory.izbirkom.ru/region/moscow_city?action=ik&vrn=4774041138728), [УИК №245](http://www.moscow_city.vybory.izbirkom.ru/region/moscow_city?action=ik&vrn=4774041138879))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/2398.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №1430](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=782000026&tvd=27820001295441&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27820001295441), [УИК №1431](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=782000026&tvd=27820001295441&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27820001295441), [УИК №1432](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=782000026&tvd=27820001295441&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27820001295441)). Адрес и члены комиссий ([УИК №1430](http://www.st-petersburg.vybory.izbirkom.ru/region/st-petersburg?action=ik&vrn=4784011343789), [УИК №1431](http://www.st-petersburg.vybory.izbirkom.ru/region/st-petersburg?action=ik&vrn=4784011343799), [УИК №1432](http://www.st-petersburg.vybory.izbirkom.ru/region/st-petersburg?action=ik&vrn=4784011343807))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/2521.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №549](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=782000014&tvd=27820001295429&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27820001295429), [УИК №553](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=782000014&tvd=27820001295429&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27820001295429)). Адрес и члены комиссий ([УИК №549](http://www.st-petersburg.vybory.izbirkom.ru/region/st-petersburg?action=ik&vrn=4784019244443), [УИК №553](http://www.st-petersburg.vybory.izbirkom.ru/region/st-petersburg?action=ik&vrn=4784019244447))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/2713.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №1942](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=782000003&tvd=27820001295418&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27820001295418), [УИК №1943](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=782000003&tvd=27820001295418&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27820001295418), [УИК №1945](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=782000003&tvd=27820001295418&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27820001295418)). Адрес и члены комиссий ([УИК №1942](http://www.st-petersburg.vybory.izbirkom.ru/region/st-petersburg?action=ik&vrn=4784028281923), [УИК №1943](http://www.st-petersburg.vybory.izbirkom.ru/region/st-petersburg?action=ik&vrn=4784028328599), [УИК №1945](http://www.st-petersburg.vybory.izbirkom.ru/region/st-petersburg?action=ik&vrn=4784028206022))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/2833.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №1721](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=782000023&tvd=27820001295438&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27820001295438), [УИК №1722](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=782000023&tvd=27820001295438&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=27820001295438)). Адрес и члены комиссий ([УИК №1721](http://www.st-petersburg.vybory.izbirkom.ru/region/st-petersburg?action=ik&vrn=4784013198867), [УИК №1722](http://www.st-petersburg.vybory.izbirkom.ru/region/st-petersburg?action=ik&vrn=4784013198869))

___

![](https://yaroslavsobolev.github.io/pages/images/vote_rigging_1/locations/uiks/4352.png)

Ссылки на официальный сайт ЦИК: Результаты голосования ([УИК №246](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=642000024&tvd=26420001638389&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=26420001638389), [УИК №247](http://www.vybory.izbirkom.ru/region/izbirkom?action=show&global=true&root=642000024&tvd=26420001638389&vrn=100100163596966&prver=0&pronetvd=null&region=0&sub_region=99&type=465&vibid=26420001638389)). Адрес и члены комиссий ([УИК №246](http://www.saratov.vybory.izbirkom.ru/region/saratov?action=ik&vrn=4644036405683), [УИК №247](http://www.saratov.vybory.izbirkom.ru/region/saratov?action=ik&vrn=4644036405496))

___



[Вот здесь](https://github.com/yaroslavsobolev/pages/tree/master/images/vote_rigging_1/locations) я выложил такие же
 графики для всех найденных мной подозрительных случаев (61 штука).

## Виски-танго-фокстрот?
 Честно 
 говоря, я 
 ожидал, 
 что мой улов будет скудным, поскольку выборка должна была получиться маленькой: я сузил её только до 
 УИКов-близнецов, причём среди них пытаюсь найти такие пары (а также тройки и четвёрки), где не все УИКи в одном 
 доме пали жертвой фальсификаций, и ищу 
 разницу ровно в тысячу голосов "да". Результат превзошёл все ожидания: улов составил десятки адресов! 
 Видимо, масштаб и разнообразие электорального жульничества на этом голосовании оказались так велики, что даже такие 
 специфические фальсификации запросто обнаруживаются в заметных количествах!

ТУДУ:
 * Исходники на гитхабе
 * Откуда взяты базы данных
 
 