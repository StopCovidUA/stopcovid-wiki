---
description: 'Інженерам, програмістам, IT аналітикам'
---

# Технології

Координация – [ищем координатора](https://trello.com/c/YRWr9gRq/36-%D0%BA%D0%BE%D0%BE%D1%80%D0%B4%D0%B8%D0%BD%D0%B0%D1%82%D0%BE%D1%80-%D0%BF%D0%BE-it-%D1%82%D0%B0-%D1%96%D0%BD%D0%B6%D0%B5%D0%BD%D0%B5%D1%80%D0%B0%D0%BC)

* [\#it-engineers](https://discord.gg/GMGzPN6)
* [\#ivl-tech](https://discord.gg/yxFSSRx) – обсуждение производства и модификации ИВЛ аппаратов
* [Чат боты для поставок еды людям на карантине](dostavka-produktov-i-medikamentov.md)
* [Система логистики](sistema-logistiki.md)

## Цели

* заонбордить в работу 400 волонтеров, 
* обработать 3000 заявок помощь

## Транспортные сервисы

Медики не знают как пользоваться, не у всех норм девайсы. Для звонков нужна автоматизация.

* [Система логистики товаров](sistema-logistiki.md)
* [Постачання продуктів, медикаментів та засобів безпеки](dostavka-produktov-i-medikamentov.md)
* [Сервисы транспортировки врачей](servisy-transportirovki-vrachei.md)
* [https://l2mtk.glideapp.io/](https://l2mtk.glideapp.io/)

## Медицинские сервисы

У нас много новых технологий: смартфоны, интерактивные карты, развитие биотехнологий эти инструменты должны быть встроены в медицинскую систему

* Щодо протокулу поведінки людям в разі захворювання, пропонують таке: «Я тобі раджу зайти на сайт Міністерства охорони здоров'я Ізраїлю. Там все розписано. В А ще там ти побачиш звіти які контактори мають надсилати»
* Инфицированные люди могут щерить своё местоположение
* Трекинг зараженных зон

### Мониторинг и предсказания

Открытие и прозрачность данных по распространению вируса. Есть [вот эти данные](https://public.tableau.com/profile/publicviz?fbclid=IwAR2nTNZDiO-GM-y2940gWCCB19xfN8X1yJMVnx0grp-OHoY6xZAT_wylyUk#!/vizhome/monitor_15841091301660/sheet0), но нужно понимать что далеко не все случаи зафиксированы. На вчера тесты были только в паре областей. Можно сравнить [с европейскими данными](https://who.maps.arcgis.com/apps/opsdashboard/index.html#/a19d5d1f86ee4d99b013eed5f637232d) и [данными Оксфордского университета](https://ourworldindata.org/coronavirus)

* открытие и прозрачность данных по распространению вируса.
* для волонтёров и доноров знание куда нужно вкладывать
* Открытая база инструментов взаимодействия соседей на уровне парадного/ЖК/микрорайона \(тесты, каналы коммуникации\)
* Предсказать где сколько медиков будет нужно когда
* Зараженность локации

### Сборка и модификация ИВЛ

[Aaron Yahalom](https://t.me/aaronyahalom) – Скажите у кого-нибудь есть знакомый реаниматолог или специалист в работе ИВЛ? Я взял сильнейшие умы Samsung, инженеров изобретателей. Есть концепция быстрого производства простейшего ИВЛ. Нужна профильная экспертиза.

> Ну про ИВЛ я из других источников от медиков знаю, что мало купить аппарат, надо его еще к кислороду подключить и запасы кислорода пополнять

Оновлення на 20-03-2020  
Провели багато досліджень по апаратам ШВЛ\(ИВЛ,ICU\), клапанам і тому подібному  
Все не так просто, як хотілося б , - в Італії клапани вирішили проблему тільки однієї лікарні, бо в них всі апарати були однакові. В Україні на даний момент 30+ різних моделей ШВЛ з роками випуску від 1995 до 2019

Ми розробили два шляхи вирішення  
1 - збираємо базу всіх ШВЛ, з командою з 30+ інженерів намагаємося знайти рішення для швидкої модернізації кожного  
Приклад [https://onlinelibrary.wiley.com/…/epdf/10…/j.aem.2006.05.009](https://onlinelibrary.wiley.com/doi/epdf/10.1197/j.aem.2006.05.009?fbclid=IwAR1IqFEQKojLgiJn4EqZ_Y0z8dAOh0kiqayevBG6avp4YhGsgkiV33obCEo)  
2 - робимо прототип свого аналога ШВЛ, на базі мішка АМБУ, це рішення коштує на декілька порядків менше самого апарату і кожен зможе запустити виробництво на місцях, вся документація є в відкритому доступі

Приклад \(відео\) [https://www.facebook.com/100002953218449/posts/2677008815740866](https://www.facebook.com/vanya.chebotaev/posts/2677008815740866?__xts__%5B0%5D=68.ARDP4VdZKlQI-NcmsFh2I6Qt2o6hTTIWVJhkJ2SrGaBxCW6HUvCm6MT8D62bGcFTkGlcc5Ri9kXvcHCJNsdQ8PhVqe1NGSYZHfZxYo7urCIYmAw2HYI8dMrLm_--qOKkL8TKPiMIiHtmI6DIglmPxkZNkXKSxHzHXxtR3q9uUatXsulAvfPx61y6g7Bm0VAPdgpiZ7uDcmkmFp3rjXsPXxQKtkjvZXixK0GWrFX0hf81vcL_EE8zLx_RfLs1LjFZ1t15ynM5VoGSOR9WhuC5DEUo1ELovhigbEnxbJIEzoTceF3LzenzSpMW_1sBYAMAD_3QruJEiT740IRKzGTZZjs&__tn__=K-R)

Прохання  
- приєднатися до спільноти [https://t.me/revelfam](https://t.me/revelfam?fbclid=IwAR39nxNQz6gwD1C4OzPkmMC0-knR07wxXoNp4KJPX44uzZsqM0r47mTbH6w) всімі інженерам, які мають ресурси і готові діяти щодо виробництва даних пристроїв  
- приєднатися лікарям, лабораторіям, поставщикам із списками і базами даних пристроїв разом із сервісними документаціями до цих пристроїв  
- допомогти в координації на місцях

[https://www.ifixit.com/Device/Ventilator](https://www.ifixit.com/Device/Ventilator)

#### Модификация существующих ИВЛ

* Как использовать один аппарат ИВЛ для нескольких пациентов [How to Use One Ventilator to Save Multiple Lives](https://www.youtube.com/watch?v=uClq978oohY&feature=youtu.be)

#### Больше ресурсов

* [https://www.3dprintingmedia.network/covid-19-3d-printed-valve-for-reanimation-device/](https://www.3dprintingmedia.network/covid-19-3d-printed-valve-for-reanimation-device/)
* [Open Source ventilator hackathon](https://hackaday.com/2020/03/12/ultimate-medical-hackathon-how-fast-can-we-design-and-deploy-an-open-source-ventilator/?fbclid=IwAR21A0LNDOajH30Shd0f7hPemwYIncr-g5dqVlqqHOWjStVO-jUaDo9TrOQ)
* [Open Source COVID19 Medical Supplies](https://www.facebook.com/groups/670932227050506/)
* [There’s A Shortage Of Ventilators For Coronavirus Patients, So This International Group Invented An Open Source Alternative That’s Being Tested Next Week](https://www.forbes.com/sites/alexandrasternlicht/2020/03/18/theres-a-shortage-of-ventilators-for-coronavirus-patients-so-this-international-group-invented-an-open-source-alternative-thats-being-tested-next-week/)
* [https://www.facebook.com/Fabricator.me/posts/3415059838521130](https://www.facebook.com/Fabricator.me/posts/3415059838521130)
* [Тренажер дыхания – стимулирующий спирометр Voldyne 5000](https://ark-ukraine.com.ua/product/%D1%82%D1%80%D0%B5%D0%BD%D0%B0%D0%B6%D0%B5%D1%80-%D0%B4%D1%8B%D1%85%D0%B0%D0%BD%D0%B8%D1%8F-%D1%81%D1%82%D0%B8%D0%BC%D1%83%D0%BB%D0%B8%D1%80%D1%83%D1%8E%D1%89%D0%B8%D0%B9-%D1%81%D0%BF%D0%B8/)
* сложнее: - кислородные маски, нужен еще кислород и обучение
* Из реально сложных вещей - кустарные аппараты ИВЛ
* [https://korrespondent.net/world/4207134-v-chekhyy-budut-pechatat-respyratory-na-3D-pryntere](https://korrespondent.net/world/4207134-v-chekhyy-budut-pechatat-respyratory-na-3D-pryntere)
* [https://osventilator.slack.com/](https://osventilator.slack.com/)
* [https://www.youtube.com/watch?v=uClq978oohY&feature=emb\_title](https://www.youtube.com/watch?v=uClq978oohY&feature=emb_title)
* Виктор Шкурба и дрон юа
* IJS, PRISTOP & GZS have initiated a respirator project Mr.Sekulic and his group have initiated a group to hack Covid-19 through developing test kits, respirators based on MITs open source plans MIT have initiated several projects with regards to Covid-19. LABENA has been helping with their lab, network, and by donating equipment since early february.
* Можно сделать саморепортинг \(анонимный\) о симптомах болезни
* Мобильные лабы для тестирования

Люди, которым предписано быть на карантине, должны установить на свой телефон специальное приложение, которое оповещает власти, если человек нарушил режим изоляции. Штраф за нарушение карантина может достигать $2500. • На телефоны приходят оповещения в случае, если поблизости выявлен случай заражения. • Также на веб-сайтах и в приложениях для смартфонов можно получить почасовые, а иногда и поминутные данные о перемещении зараженных людей — какие автобусы они использовали, когда и куда они садились и выходили, даже информацию о том, носили ли они защитные маски. Как это работает, посмотрите сами

[https://coronamap.site/](https://coronamap.site/)

### Unsorted

* Чат бот координации волонтеров \(Виталик\)
* v2020 \(Солидарность\)
* poboremo \(Институт будущего\)
* [https://covid-19.lvivoblrada.gov.ua/](https://covid-19.lvivoblrada.gov.ua/) \(SoftServe\)
* donor.org \(каким больницам что нужно\)
* [https://pandemiia.herokuapp.com/](https://pandemiia.herokuapp.com/)
* AirBNB
* Сборки ИВЛ \(маски, разветвители\)
* Кварцевые лампы, обеззараживатели воздуха
* QR коды для зоны карантина
* Фейс трекинг
* Дешборды показывают кто где заразился \(по области\)
* Трекинг зараженности района \(микрорайоны\)
* Модели предсказаний
* Штрихкод-Браслеты с привязкой к медкарте
* Експрес-діагностика COVID-19 за допомогою системи машинного зору \(микроскоп и томография\)
* Система запросов больниц
* Распределенное вычисление белков / вируса
* [https://hospitalrun.io/blog/why-hospitalrun/](https://hospitalrun.io/blog/why-hospitalrun/)
* [Sanju 'Amorn' Sachamuneewongse](https://www.facebook.com/awesomesanju?comment_id=Y29tbWVudDozMDkxMjgyNTA0MjIzNjE1XzMwOTE0MjQ2MDQyMDk0MDU%3D) In Thailand they have created a Thailand Digital Covid Group to bring in all working in programming and tech to create the easiest way to track cases within Thailand and find out which stores have masks and hand sanitizers available and how many.
* [Rositsa Zaimova](https://www.facebook.com/rosi.zaimova?comment_id=Y29tbWVudDozMDkxMjgyNTA0MjIzNjE1XzMwOTIyNDI4NjQxMjc1Nzk%3D) My team and I at Dalberg Data Insights are developing predictive models using mobility and health data. Hoping to have first results in Belgium before end of the week and then scale, Europe, the world.
* По типам влияния [https://helpwithcovid.com/projects](https://helpwithcovid.com/projects)
* [https://stopcorona.live/](https://stopcorona.live/)

Track the outbreak Reduce spread Scale testing Medical facilities Medical equipments Treatment R&D E-Learning Job placement Mental health Help out communities Map volunteers to needs News and information Social giving Other

### Идеи

* [Українська спільнота інженерної допомоги медичним закладам](https://t.me/UCEAMI)
* [https://www.firstpost.com/tech/news-analysis/chinese-citizens-turn-to-virus-tracker-apps-to-avoid-infected-neighbourhoods-7998181.html](https://www.firstpost.com/tech/news-analysis/chinese-citizens-turn-to-virus-tracker-apps-to-avoid-infected-neighbourhoods-7998181.html)
* [https://rtvi.com/news/china-app-virus/](https://rtvi.com/news/china-app-virus/)
* Individuals used the platform to share reports, voluntarily and in real time, about symptoms using a variety of media \(such as a call-in line and smartphones\); this information was quickly verified and collated. The result was then combined with more community-created apps that allowed users to download their smartphone location history to determine if they may have been exposed.
* Taiwan \(best: Bottom-up information sharing, public-private partnerships, “hacktivism” \(activism through the building of quick-and-dirty but effective proofs of concept for online public services\), and participatory collective action have been central to the country’s success in coordinating a consensual and transparent set of responses to the coronavirus.
* Аудит информ. мед систем с Натой
* [https://vitagramma.com/](https://vitagramma.com/)
* Контроль симптомов через страховые
* Распределённая медицина, дневные отчеты и браслеты
* [https://www.telegraph.co.uk/news/2020/03/29/germany-will-issue-coronavirus-antibody-certificates-allow-quarantined/](https://www.telegraph.co.uk/news/2020/03/29/germany-will-issue-coronavirus-antibody-certificates-allow-quarantined/)

## Хакатоны

* [https://www.coronawhy.org/](https://www.coronawhy.org/)
* [https://garage48.org/hackthecrisis](https://garage48.org/hackthecrisis)
* [https://medium.com/daia/the-covidathon-decentralised-ai-against-covid-19-a27d5a25e199](https://medium.com/daia/the-covidathon-decentralised-ai-against-covid-19-a27d5a25e199)
* [COVID-19 Slack / Discord workspaces \(+ hackathons\) – International list](https://docs.google.com/document/d/e/2PACX-1vS2p8BPJ5d0WcHxRAB0BWCv6fY2lgZPVanfZNqOX4z2e00cOEwPIWhlO5ZNlPb5Fe2Pva_c74leKrR2/pub)



Ниже подборка хакатонов и проектов, в которые можно вписаться pro bono, чтобы помочь в борьбе с эпидемией и ее последствиями:

Хакатоны:

Pandemic Response Hackathon \([https://datavant.com/pandemic-response-hackathon/](https://datavant.com/pandemic-response-hackathon/)\) пытаются лучше понять эпидемию и бороться с распростраением вируса.

CodeVsCOVID19 \([https://www.codevscovid19.org/](https://www.codevscovid19.org/)\) с очень большим количеством идей, как можно помочь.

Hack quarantine \([https://hackquarantine.com/info.html](https://hackquarantine.com/info.html)\) с нескольктими треками: supporting quarantined, tech and health, remote working, improving awareness and behaviour.

Задача на моделирование распространения вируса \([https://zindi.africa/competitions/predict-the-global-spread-of-covid-19](https://zindi.africa/competitions/predict-the-global-spread-of-covid-19)\) из Африки с призовым фондом.

На Kaggle:

Предлагают предсказать скорость распространения \([https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset/tasks?taskId=508&utm\_medium=email&utm\_source=intercom&utm\_campaign=tasks-award-march-2020](https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset/tasks?taskId=508&utm_medium=email&utm_source=intercom&utm_campaign=tasks-award-march-2020)\) вируса, есть открытый датасет.

Сейчас выходит много медицинских статей про коронавирус, все прочитать невозможно. Есть задача \([https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge](https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge)\) помочь медикам быстрее вытаскивать из текстов важную информацию с помощью ML.

ВОЗ хотят вычислить \([https://www.kaggle.com/c/covid19-global-forecasting-week-1/](https://www.kaggle.com/c/covid19-global-forecasting-week-1/)\), какие именно факторы влияют на распространение вируса и смертность.

Проекты:

COVIDарность \([https://t.me/covidarnost](https://t.me/covidarnost)\) в России помогают создавать сообщества для взаимопомощи в эпидемию. Сейчас ищут фронтенд, бэкенд разработчиков и тех, у кого есть опыт с ботами.

Folding@home \([https://foldingathome.org/2020/03/15/coronavirus-what-were-doing-and-how-you-can-help-in-simple-terms/](https://foldingathome.org/2020/03/15/coronavirus-what-were-doing-and-how-you-can-help-in-simple-terms/)\) занимаются численным моделированием, чтобы найти лекарство от коронавируса и им можно помочь с распределенными вычислениями.

Другие списки:

helpwithcovid.com \([http://helpwithcovid.com/](http://helpwithcovid.com/)\), который делает CEO OpenAI, собирает инициативы, там можно нафильтровать себе проект по навыкам/профессии.

Coronavirus handbook \([https://coronavirustechhandbook.com/home](https://coronavirustechhandbook.com/home)\): еще больше проектов и сообществ для тех, кто может прогать \([https://coronavirustechhandbook.com/techcommunities](https://coronavirustechhandbook.com/techcommunities)\).

Еще один список от 8000hours \([https://80000hours.org/covid-19/?fbclid=IwAR0cDD5elhfyzf1Dk1i2HEffMG\_DsptYARXZlk-Dvxf\_-VxgKrqupGhW42s\#work-on-covid-19](https://80000hours.org/covid-19/?fbclid=IwAR0cDD5elhfyzf1Dk1i2HEffMG_DsptYARXZlk-Dvxf_-VxgKrqupGhW42s#work-on-covid-19)\) с большим гуглдоком \([https://docs.google.com/spreadsheets/d/1tZoltKBNVCIqhl9iv14jK5N4jF5N52uFyzorPdrytqc/edit\#gid=0](https://docs.google.com/spreadsheets/d/1tZoltKBNVCIqhl9iv14jK5N4jF5N52uFyzorPdrytqc/edit#gid=0)\), который постоянно обновляют.

В Twitter:

Ищите \([https://twitter.com/hashtag/COVTECH?src=hashtag\_click](https://twitter.com/hashtag/COVTECH?src=hashtag_click)\) инициативы по хэштегу \#COVTECH.

Если встретите еще интересные ссылки, скиньте их мне, пожалуйста, в личку или в фидбэк, а я дополню список. Лайк, репост, санитайзер. 🐠

## Идеи

* [https://epidemic-stats.com/](https://epidemic-stats.com/)
* [https://www.wired.com/story/opinion-ai-is-an-ideology-not-a-technology/](https://www.wired.com/story/opinion-ai-is-an-ideology-not-a-technology/)
* [How Civic Technology Can Help Stop a Pandemic](https://www.foreignaffairs.com/articles/asia/2020-03-20/how-civic-technology-can-help-stop-pandemic)
* [https://app.powerbi.com/view?r=eyJrIjoiN2M1MTY1MDktZTY5Mi00OTE0LWFiMDAtMjM4NTY0YWU2MmI3IiwidCI6IjI4OGJmYmNmLTVhYjItNDk2MS04YTM5LTg2MDYxYWFhY2Q4NiIsImMiOjl9](https://app.powerbi.com/view?r=eyJrIjoiN2M1MTY1MDktZTY5Mi00OTE0LWFiMDAtMjM4NTY0YWU2MmI3IiwidCI6IjI4OGJmYmNmLTVhYjItNDk2MS04YTM5LTg2MDYxYWFhY2Q4NiIsImMiOjl9)
* [https://www.facebook.com/1398461359/posts/10217596251643635/?d=n](https://www.facebook.com/1398461359/posts/10217596251643635/?d=n)
* Отсмотреть решения с хакатонов
* в Корее есть апка, которая сообщает о зараженности в регионе и дает точный маршрут к центру госпитализации
* Аппка с анализами которые трекают где ты и какие к тебя хронические проблемы
* Monitoring, Distributed healthcare
* [https://www.ycombinator.com/covid](https://www.ycombinator.com/covid)

