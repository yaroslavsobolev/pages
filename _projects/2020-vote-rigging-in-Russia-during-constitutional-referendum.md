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

> "Смотрите внимательно, внучата, как ваш дедуля сейчас заменит единичку на нолик и тем самым разрушит целую 
галактическую империю одним махом." — Рик Санчез

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
голосовании", я сфокусируюсь в этом посте лишь на одной специальной их разновидности. На это меня вдохновила 
следующая примечательная разница между итоговым протоколом, полученным членом избирательной 
комиссии №800 в Якутске (фото протокола — слева), и данными в 
официальной базе данных ЦИК (справа — скриншот вот
 [этой](http://www.vybory.izbirkom.ru/region/region/izbirkom?action=show&root=142000064&tvd=21420001011794&vrn=100100163596966&region=0&global=true&sub_region=99&prver=0&pronetvd=null&vibid=21420001011794&type=465) 
 страницы):
 
![](/pages/images/vote_rigging_1/uik800.jpg)

*Источник: [Твиттер](https://twitter.com/k_b_l_v/status/1279566757485637633) и 
["Новости Якутии"]((https://news.ykt.ru/article/103260?utm_source=tw&utm_medium=so&utm_campaign=izbirkom-yakutska-rasskazal-ob-oshibkah-v))*

Вглядитесь в отличающиеся цифры (помечено жёлтым): в базе данных (справа) цифра в разряде тысяч изменена с нуля на 
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

*Официальные результаты голосования 1 июля в Москве и Хабаровском крае, показанные в виде столбиков (по одному 
столбику на УИК), чья высота соответствует проценту голосов "да" на участке. Серыми рамками обведены УИКи одного 
ТИКа (то есть, географически близкие друг к другу). Автор визуализации: 
[Денис Ольшин](https://twitter.com/denullru/status/1279042332256620546). 
Посмотреть и потрогать эту визуализацию целиком — можно [здесь](https://popravke.net/anomalies.html).*
 
Такое отображение (его ещё называют 
["диаграммой Габдульвалеева"](https://www.electoral.graphics/ru-ru/laboratory/gab)) полезно для обнаружения УИКов, 
где число голосов "да" и/или явка разительно отличаются (иногда в два-три раза) от географически-соседних с 
ними УИКов. Такие аномальные выбросы (на рисунке выше это красные столбики) не наблюдаются в исторических данных 
честных выборов демократических стран, и не имеют объяснения в каких-либо причудах реального поведения избирателей. 
Вы можете возразить: "А вдруг все консервативные бабули района живут в одном квартале? Они-то и дают это различие". В 
ответ я попытаюсь найти среди этих соседей-УИКов, резко разнящихся по результату, не просто соседей по району, а 
соседей **по дому**: иногда более одного УИКа имеют один и тот же адрес (чаще всего это здание общеобразовательной 
  школы). Согласитесь: было бы уж совсем необъяснимо, если бы избиратели, приходящие голосовать в одно и то же здание по
   месту жительства, голосовали бы совершенно по-разному в разных *комнатах* этого здания. Но уж совсем 
   сверхъестественно то, что в некоторых случаях такие УИКи отличаются ровно на тысячу голосов "да". Вот несколько 
   примеров:
  
  
![](/pages/images/vote_rigging_1/84.png)

 Идея этой визуализации у неё примерно та же, что и у , только выполнена она намного 
 нагляднее и интегрирована с отображением места конкретного ТИК и УИК в распределениях по осям явка-результат.
 Честно 
 говоря, я 
 ожидал, 
 что мой улов будет скудным, поскольку выборка должна была получиться маленькой: я сузил её только до 
 УИКов-близнецов, причём среди них пытаюсь найти такие пары (а также тройки и четвёрки), где не все УИКи в одном 
 доме пали жертвой фальсификаций, и ищу 
 разницу ровно в тысячу голосов "да". Результат превзошёл все ожидания: улов составил десятки адресов! 
 Видимо, масштаб и разнообразие электорального жульничества на этом голосовании оказались так велики, что даже такие 
 специфические фальсификации запросто обнаруживаются в заметных количествах!

**Obviously,** we’ve styled up *all the basic* text formatting options [available in markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).


![](/pages/images/vote_rigging_1/84.png)



You can create lists:

* Simple bulleted lists
* Like this one
* Are cool

And:

1. Numbered lists
2. Like this other one
3. Are great too

You can also add blockquotes, which are shown at a larger width to help break up the layout and draw attention to key parts of your content:

> “Simple can be harder than complex: You have to work hard to get your thinking clean to make it simple. But it’s worth it in the end because once you get there, you can move mountains.”

The theme also supports markdown tables:

| Item                 | Author        | Supports tables? | Price |
|----------------------|---------------|------------------|-------|
| Duet Jekyll Theme    | Jekyll Themes | Yes              | $49   |
| Index Jekyll Theme   | Jekyll Themes | Yes              | $49   |
| Journal Jekyll Theme | Jekyll Themes | Yes              | $49   |

And footnotes[^1], which link to explanations[^2] at the bottom of the page[^3].

[^1]: Beautiful modern, minimal theme design.
[^2]: Powerful features to show off your work.
[^3]: Maintained and supported by the theme developer.

You can throw in some horizontal rules too:

---

### Image galleries

Here's a really neat custom feature we added – galleries:

<div class="gallery" data-columns="3">
	<img src="/pages/images/demo/demo-portrait.jpg">
	<img src="/pages/images/demo/demo-landscape.jpg">
	<img src="/images/demo/demo-square.jpg">
	<img src="/images/demo/demo-landscape-2.jpg">
</div>

Inspired by the Galleries feature from WordPress, we've made it easy to create grid layouts for your images. Just use a bit of simple HTML in your post to create a masonry grid image layout:

```html
<div class="gallery" data-columns="3">
    <img src="/images/demo/demo-portrait.jpg">
    <img src="/images/demo/demo-landscape.jpg">
    <img src="/images/demo/demo-square.jpg">
    <img src="/images/demo/demo-landscape-2.jpg">
</div>
```

*See what we did there? Code and syntax highlighting is built-in too!*

Change the number inside the 'columns' setting to create different types of gallery for all kinds of purposes. You can even click on each image to seamlessly enlarge it on the page.

---

### Image carousels

Here's another gallery with only one column, which creates a carousel slide-show instead.

A nice little feature: the carousel only advances when it is in view, so your visitors won't scroll down to find it half way through your images.

<div class="gallery" data-columns="1">
	<img src="/pages/images/demo/demo-landscape.jpg">
	<img src="/pages/images/demo/demo-landscape-2.jpg">
</div>

### What about videos?

Videos are an awesome way to show off your work in a more engaging and personal way, and we’ve made sure they work great on our themes. Just paste an embed code from YouTube or Vimeo, and the theme makes sure it displays perfectly:

<iframe src="https://player.vimeo.com/video/148003889" width="640" height="360" frameborder="0" allowfullscreen></iframe>

---

## Pretty cool, huh?

We've packed this theme with powerful features to show off your work.

Why not put them to use on your new portfolio?

<a href="https://jekyllthemes.io/theme/duet-portfolio-jekyll-theme" class="button button--large">Get This Theme</a>