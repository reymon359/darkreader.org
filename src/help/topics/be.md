# Даведка (Беларуская)

Гэты дакумент раскажа вам аб асноўных магчымасцях Дарк Рыдэр.

- [Часта задаваемыя пытанні](#faq)
- [Контакты](#contacts)
- [Верхняя секцыя](#top-section)
- [Налады фільтра](#filter-settings)
- [Налады для канкрэтнага сайта](#custom-site-settings)
- [Спіс сайтаў](#site-list)
- [Укладка Яшчэ](#more-tab)
- [Рэжымы генерацыі тэм](#theme-generation-modes)
- [Ніжняя секцыя](#bottom-section)
- [Выкарыстанне Інструментаў распрацоўніка](#using-dev-tools)


<h2 id="top-section">Верхняя секцыя</h2>

<img src="/images/help/darkreader-top-section.png" alt="Верхняя секцыя" style="width: 15rem;" />

- Кнопка **Пераключыць** дадае сайт у спіс выключэнняў (альбо дастае адтуль).
- Пераключальнік **Укл/Выкл** ўключае альбо выключае пашырэнне.
- Націсніце на спасылкі пад кнопкамі для ўстаноўкі **спалучэнняў клавіш**.
- Калі кнопка пераключэння прыцемненая, гэта значыць, што браўзэр блакуе пашырэння на гэтай старонцы.


<h2 id="filter-settings">Налады фільтра</h2>

<img src="/images/help/darkreader-filter-settings.png" alt="Налады фільтра" style="width: 15rem;" />

Наладзьце значэння фільтра, якія адпавядаюць параметрам вашага экрана і асвятленні ў пакоі.


<h2 id="custom-site-settings">Налады для канкрэтнага сайта</h2>

<img src="/images/help/darkreader-custom-site-settings.png" alt="Налады для канкрэтнага сайта" style="width: 15rem;" />

Кнопка **Толькі для** прымяняе налады толькі для бягучага сайта.

Націсніце на кнопку, наладзьце фільтр, націсніце яшчэ раз для адмены.


<h2 id="site-list">Спіс сайтаў</h2>

<img src="/images/help/darkreader-site-list.png" alt="Спіс сайтаў" style="width: 15rem;" />

- Выкарыстоўвайце **Інвертаваць толькі гэтыя**, калі вы хочаце, каб Dark Reader працаваў толькі на сайтах у спісе.
- **Не інвертаваць** прадухіліць працу пашырэння на сайтах у спісе.
- Магчымыя значэння: `google.com, mail.google.com, google. *, Google.com / maps` і т.п.
- Націск кнопкі **Пераключыць**, апісанай вышэй, дадае бягучы сайт у гэты спіс.

<h2 id="more-tab">Укладка Яшчэ</h2>

<img src="/images/help/darkreader-more-tab.png" alt="Укладка Яшчэ" style="width: 15rem;" />

- **Выберыце шрыфт** са спісу (або ўвядзіце поўнае імя шрыфта ў Firefox), націсніце галачку.
- Наладзьце **абводку тэксту**.
- Выберыце рэжым **генерацыі тэм**.


<h2 id="theme-generation-modes">Рэжымы генерацыі тэм</h2>

<figure>
    <img src="/images/help/darkreader-theme-modes.png" alt="Фільтр + vs. Статычны vs. Дынамічны рэжым" />
    <figcaption>Фільтр + vs. Статычны vs. Дынамічны рэжым</figcaption>
</figure>

- **Фільтр** - Першапачатковы рэжым у Dark Reader заснаваны на CSS фільтрах.
Ён **інвертуе ўсю старонку** і **рэвертуе** пэўныя часткі назад.
Патрабавальны да графічнага працэсара.
**Хуткі**, але мае некаторыя недахопы:
адключае тэхналогію субпiксельнага рэндэрынгу,
інвертуе цёмныя ўчасткі ў светлыя,
запавольвае працу браўзэра на вялікіх старонках,
ня адлюстроўвае некаторыя старонкі ў Firefox.
- **Фільтр+** - той жа, што і Фільтр, але заснаваны на спецыяльных SVG фільтрах
якія **лепш апрацоўваюць колеры** робячы карцінкі менш цьмянымі.
Дрэнна працуе ў Firefox.
- **Статычны** - імгненна генеруе простую тэму.
- **Дынамiчны** - аналізуе стылі бягучай вэб-старонкі, фонавыя малюнкі, вектарную графіку.
Патрабуе больш рэсурсаў пры пачатковай загрузцы старонкі,
але выдае **найлепшыя** візуальныя вынікі.
Праца над гэтым рэжымам у працэсе,
але ён ужо выдатна працуе на большасці сучасных сайтаў.


<h2 id="bottom-section">Ніжняя секцыя</h2>

<img src="/images/help/darkreader-footer.png" alt="Ніжняя секцыя" style="width: 15rem;" />

- Прачытайце нашу **палітыку прыватнасці**, падпісвайцеся на наш **Twitter**.
- **Падтрымка** - калі вам падабаецца Dark Reader, падтрымайце яго актыўную распрацоўку.
Збор сродкаў вядзе Open Collective, які ў цяперашні час выкарыстоўвае Stripe для ажыццяўлення плацяжоў.
- **Навіны** - апавяшчае аб абнаўленнях прыкладання і важных падзеях.
- **Інструменты распрацоўніка** - адчыняе рэдактар правак рэжыму генерацыі тэм.


<h2 id="using-dev-tools">Выкарыстанне Інструментаў распрацоўніка</h2>

Калі вы знаёмыя з CSS селектарамі, вы можаце прапанаваць праўку для якога-небудзь вэб-сайта.
Больш інфармацыі аб інструментах распрацоўніка [тут](https://github.com/darkreader/darkreader#how-to-contribute).


<h2 id="faq">Часта задаваемыя пытанні</h2>

#### Пашырэнне просіць правы на чытанне маіх наведаных сайтаў

Пашырэнню патрэбныя дадзеныя правы для магчымасці аналізу і змены вонкавага выгляду вэб-старонак, вызначэння,
ці адключаны бягучы вэб-сайт наладамі карыстальніка або выкарыстання спецыяльных налад для бягучага сайта.
Мы не ўбудоўваем рэкламу, не збіраем дадзеныя карыстальнікаў і нікуды іх ня адсылаем.
Зыходны код пашырэння цалкам адкрыты і не мае зашыфраваных месцаў.
Наша манетызацыя празрыстая і грунтуецца на добраахвотнай дапамоге ад карыстальнікаў.

#### Старонка крамы пашырэньняў і старонкі налад браўзэра застаюцца белымі

У пашырэння няма правоў доступу да гэтых старонках.

#### Новая ўкладка і тэма браўзэра застаюцца светлымі

Пашырэнне не мае доступу да новай ўкладцы і тэмы браўзэра (можа змяняць тэму браўзэра пачынаючы з Firefox 60).
Усталюйце цёмную тэму альбо пашырэнне, якое замяняе новую ўкладку, у краме пашырэнняў.

#### Пашырэнне наогул не працуе

Калі ў сістэме ўсталяваныя падобныя пашырэння з цёмным рэжымам, адключыце іх, перазагрузіце ўкладкі.
Націсніце значок Dark Reader, пераканайцеся што кнопка ў правым верхнім куце знаходзiцца ў становішчы **Укл**.
Адкрыйце ўкладку **Спіс сайтаў**, праверце, што вылучана **Не інвертаваць**.
Калі нічога не дапамагае, значыць усё зусім дрэнна, напішыце нам на e-mail.

#### Сайт адлюстроўваецца некарэктна ці працуе павольна

Калі ласка, дашліце адрас сайта, скрыншот, версіі аперацыйнай сістэмы і браўзэра на наш e-mail.
Мы паспрабуем вызначыць прычыну, па меншай меры для папулярнага вэб-сайта.
Таксама паспрабуйце змяніць **рэжым генерацыі тэм** або паспрабуйце выкарыстоўваць **Светлы рэжым**.
Праверце, што сайт адсутнічае ў **Спісе сайтаў**.

#### Пашырэнне не працуе ў рэжыме інкогніта

Адчыніце старонку **chrome://extensions**, знайдзіце **Dark Reader**, націсніце **Дазволіць выкарыстанне ў рэжыме інкогніта**.

#### Пашырэнне не працуе для лакальных файлаў

Адчыніце старонку **chrome://extensions**, знайдзіце **Dark Reader**, націсніце **Дазволіць адкрываць лакальныя файлы па спасылках**.

#### Сайт зусім не адлюстроўваецца ў рэжыме Фільтр

Калі вы карыстальнік Chrome на Mac OS, абнавіце Mac OS да версіі 10.13, гэта павінна абнавіць відэа драйверы.
Калі вы карыстальнік Firefox, верагодна гэта баг браўзэра, выкарыстоўвайце іншы рэжым для такіх сайтаў.


<h2 id="contacts">Кантакты</h2>

Па ўсіх пытаннях пішыце на [darkreaderapp@gmail.com](mailto:darkreaderapp@gmail.com)