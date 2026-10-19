# ══════════════════════════════════════════════════════════════
# ТЕКСТОВЕ НА САЙТА — АНГЛИЙСКИ (English)
# ══════════════════════════════════════════════════════════════
#
# КАК СЕ РЕДАКТИРА
#  • Променяй само текста СЛЕД двуеточието. Думата преди двуеточието (ключът) не се пипа.
#  • Редовете, които започват с #, са бележки и не се показват на сайта.
#  • Един текст може да е на няколко реда: следващите редове започват с 4 интервала.
#  • След промяна: запази файла → GitHub Desktop → Commit → Push origin → изчакай 1–2 минути → Ctrl+F5.


# ──────────────────────────────────────────────────────────────
# ОБЩО ЗА СТРАНИЦАТА И БУТОНИТЕ
# ──────────────────────────────────────────────────────────────

# Заглавие на страницата (показва се в раздела на браузъра)
pageTitle: Property statistics

# Меню вляво — първи бутон
navAgency: Registry Agency

# Меню вляво — втори бутон
navBnb: BNB

# Меню вляво — бутон „Контакти“
navContacts: Contacts

# Съобщение за раздел, който още не е готов
comingSoon: This section is coming soon.

# Първият избор в списъка със служби
allCountry: All Bulgaria

# Заглавие на колоната с тримесечията във файловете за сваляне
quarter: Quarter

# Горе вляво в таблицата под графиката
thIndicator: Indicator

# Мерна единица в скоби до името на показателя
unitCount: count

# Съобщение, докато се зареждат данните
loading: Loading data from the database…

# Съобщение при грешка с базата данни
errTitle: The data could not be loaded from the database.

# Съобщение, когато config.js не е попълнен
errNoCfg: No Supabase connection: fill in supabaseUrl and anonKey in config.js.

# Подсказка на бутона „стълбове“
labBar: Bars

# Подсказка на бутона „линия“
labLine: Line

# Подсказка на бутона с етикета, когато числата се виждат
tagOn: Hide values on the chart

# Подсказка на бутона с етикета, когато числата са скрити
tagOff: Show values on the chart

# Подсказка на бутона за средна линия, когато е включена
avgOn: Hide the average line

# Подсказка на бутона за средна линия, когато е изключена
avgOff: Show the average line for the period

# Дума „Средно“ при средната линия и в подсказката
avg: Avg

# Подсказка на окото — скриване на показател
hide: Hide

# Подсказка на окото — показване на показател
show: Show

# Надпис на бутона за сваляне
download: Download

# Сваляне — картинка
dlPng: Image (PNG)

# Сваляне — Excel таблица
dlXlsx: Table (Excel)

# Сваляне — CSV таблица
dlCsv: Table (CSV)

# Съобщение, ако свалянето не успее
dlErr: Download failed. Please try again.

# Подсказка на бутона за тъмен режим
themeToDark: Dark mode

# Подсказка на бутона за светъл режим
themeToLight: Light mode

# Подсказка на бутона за език (към кой език превключва)
langTo: Български

# Подсказка — една графика с два показателя
viewOne: One chart with two indicators

# Подсказка — две графики една до друга
viewTwo: Two charts side by side, one indicator each

# Описание на двата бутона за изглед (за екранни четци)
viewGroup: Chart layout

# Подсказка на бутона „!“
infoBtn: About the data

# Описание на избора на служба (за екранни четци)
officeLabel: Registry office

# Бърз период — 1 година
p1: 1 y

# Бърз период — 5 години
p5: 5 y

# Бърз период — 10 години
p10: 10 y

# Бърз период — всички данни
pAll: All

# Заглавие на прозореца с „!“
infoTitle: About the data

# Адрес на връзката към източника в прозореца с „!“
sourceUrl: https://www.registryagency.bg/bg/registri/imoten-registar/statistika/

# Надпис на връзката към източника
sourceLabel: Statistics page (in Bulgarian)



# ──────────────────────────────────────────────────────────────
# ГРАФИКА 1 — Продажби на имоти (ключове с префикс s.)
# ──────────────────────────────────────────────────────────────

# Голямото заглавие над графиката
s.title: Property sales

# Подзаглавие под него
s.sub: Number of registered sales by quarter and the change versus the same quarter of the
    previous year.

# Заглавие на таблицата под графиката
s.table: Values by quarter

# Описание на графиката за екранни четци (когато са двата показателя)
s.chartPair: Chart of sales and year-over-year change by quarter

# Описание на графиката за екранни четци (когато е само един показател; след него се добавя името)
s.chartOne: Chart:

# Пълно име — в легендата под графиката и в подсказката при посочване
s.sales.name: Sales

# Кратко име — в реда за средна стойност
s.sales.short: Sales

# Име на реда в таблицата под графиката
s.sales.row: Sales (count)

# Пълно име — в легендата под графиката и в подсказката при посочване
s.yoy.name: Change vs. the same quarter of the previous year

# Кратко име — в реда за средна стойност
s.yoy.short: YoY change

# Име на реда в таблицата под графиката
s.yoy.row: YoY change (%)

# Прозорец „!“ — заглавие на параграф 1
s.info1.h: What it shows

# Прозорец „!“ — текст на параграф 1
s.info1.p: The number of registered real-estate sales in each registry office, by quarter, and
    how much higher or lower that is than the same quarter a year earlier.

# Прозорец „!“ — заглавие на параграф 2
s.info2.h: How the change is calculated

# Прозорец „!“ — текст на параграф 2
s.info2.p: (Sales in the quarter − sales in the same quarter of the previous year) ÷ sales in
    the same quarter of the previous year × 100. We compare Q3 with Q3, not with the
    previous quarter, so seasonality does not distort the result.

# Прозорец „!“ — заглавие на параграф 3
s.info3.h: Source

# Прозорец „!“ — текст на параграф 3
s.info3.p: Registry Agency (Bulgaria), registrations reports by office.

# Прозорец „!“ — заглавие на параграф 4
s.info4.h: Limitations

# Прозорец „!“ — текст на параграф 4
s.info4.p: The report has no breakdown by property type, so the numbers are not
    residential-only.



# ──────────────────────────────────────────────────────────────
# ГРАФИКА 2 — Ипотеки и дял на финансираните сделки (ключове с префикс m.)
# ──────────────────────────────────────────────────────────────

# Голямото заглавие над графиката
m.title: Mortgages and share of financed deals

# Подзаглавие под него
m.sub: Total registered mortgages (contractual + statutory) and what percentage of sales
    they represent.

# Заглавие на таблицата под графиката
m.table: Values by quarter

# Описание на графиката за екранни четци (когато са двата показателя)
m.chartPair: Chart of mortgages and the share of financed deals by quarter

# Описание на графиката за екранни четци (когато е само един показател; след него се добавя името)
m.chartOne: Chart:

# Пълно име — в легендата под графиката и в подсказката при посочване
m.mort.name: Total mortgages

# Кратко име — в реда за средна стойност
m.mort.short: Total mortgages

# Име на реда в таблицата под графиката
m.mort.row: Total mortgages

# Поясняващ текст под името в легендата
m.mort.desc: Sum of the “Contractual mortgages” and “Statutory mortgages” columns in the Registry
    Agency report.

# Пълно име — в легендата под графиката и в подсказката при посочване
m.leg.name: Statutory mortgages

# Име на реда в таблицата под графиката
m.leg.row: Statutory mortgages

# Пълно име — в легендата под графиката и в подсказката при посочване
m.con.name: Contractual mortgages

# Име на реда в таблицата под графиката
m.con.row: Contractual mortgages

# Пълно име — в легендата под графиката и в подсказката при посочване
m.share.name: Share of financed deals

# Кратко име — в реда за средна стойност
m.share.short: Share of financed deals

# Име на реда в таблицата под графиката
m.share.row: % of purchases with a mortgage

# Прозорец „!“ — заглавие на параграф 1
m.info1.h: What it shows

# Прозорец „!“ — текст на параграф 1
m.info1.p: How many mortgages were registered in each office by quarter (blue bars) and what
    percentage of that quarter's sales they represent (orange bars).

# Прозорец „!“ — заглавие на параграф 2
m.info2.h: Total mortgages

# Прозорец „!“ — текст на параграф 2
m.info2.p: The sum of two columns in the Registry Agency report: Contractual mortgages (darker
    blue part) + Statutory mortgages (lighter blue part). The two parts are stacked into
    one bar.

# Прозорец „!“ — заглавие на параграф 3
m.info3.h: Share of financed deals

# Прозорец „!“ — текст на параграф 3
m.info3.p: (Statutory mortgages + Contractual mortgages) ÷ Sales × 100, for the same office and
    quarter.

# Прозорец „!“ — заглавие на параграф 4
m.info4.h: Limitations

# Прозорец „!“ — текст на параграф 4
m.info4.p: Mortgage data starts in 2006 Q2. This is a ratio of two separate counters in the
    report, not a tracking of individual deals: one purchase can have more than one
    mortgage, and a mortgage can be registered without a purchase. The share is
    therefore an approximate estimate of credit financing.



# ──────────────────────────────────────────────────────────────
# ГРАФИКА 3 — Нови и заличени ипотеки (ключове с префикс d.)
# ──────────────────────────────────────────────────────────────

# Голямото заглавие над графиката
d.title: New and deleted mortgages

# Подзаглавие под него
d.sub: How many new mortgages were registered and how many mortgages were deleted, by
    quarter.

# Заглавие на таблицата под графиката
d.table: Values by quarter

# Описание на графиката за екранни четци (когато са двата показателя)
d.chartPair: Chart of new and deleted mortgages by quarter

# Описание на графиката за екранни четци (когато е само един показател; след него се добавя името)
d.chartOne: Chart:

# Пълно име — в легендата под графиката и в подсказката при посочване
d.nw.name: New mortgages

# Кратко име — в реда за средна стойност
d.nw.short: New mortgages

# Име на реда в таблицата под графиката
d.nw.row: New mortgages (total)

# Поясняващ текст под името в легендата
d.nw.desc: Sum of the “Contractual mortgages” and “Statutory mortgages” columns in the Registry
    Agency report.

# Пълно име — в легендата под графиката и в подсказката при посочване
d.leg.name: Statutory mortgages

# Име на реда в таблицата под графиката
d.leg.row: Statutory mortgages

# Пълно име — в легендата под графиката и в подсказката при посочване
d.con.name: Contractual mortgages

# Име на реда в таблицата под графиката
d.con.row: Contractual mortgages

# Пълно име — в легендата под графиката и в подсказката при посочване
d.del.name: Deleted mortgages

# Кратко име — в реда за средна стойност
d.del.short: Deleted mortgages

# Име на реда в таблицата под графиката
d.del.row: Deleted mortgages

# Прозорец „!“ — заглавие на параграф 1
d.info1.h: What it shows

# Прозорец „!“ — текст на параграф 1
d.info1.p: How many new mortgages were registered in each office by quarter (blue bars) and how
    many mortgages were deleted in the same quarter (orange bars).

# Прозорец „!“ — заглавие на параграф 2
d.info2.h: New mortgages

# Прозорец „!“ — текст на параграф 2
d.info2.p: The sum of two columns in the Registry Agency report: Contractual mortgages (darker
    blue part) + Statutory mortgages (lighter blue part). The two parts are stacked into
    one bar.

# Прозорец „!“ — заглавие на параграф 3
d.info3.h: Deleted mortgages

# Прозорец „!“ — текст на параграф 3
d.info3.p: The value of the “Deleted mortgages” column in the Registry Agency report.

# Прозорец „!“ — заглавие на параграф 4
d.info4.h: Limitations

# Прозорец „!“ — текст на параграф 4
d.info4.p: Mortgage data starts in 2006 Q2. The two bars are separate counters for the quarter:
    deleted mortgages are often from earlier years, so the difference between them is
    not the exact net growth of mortgages.



# ──────────────────────────────────────────────────────────────
# ГРАФИКА 4 — Възбрани (ключове с префикс v.)
# ──────────────────────────────────────────────────────────────

# Голямото заглавие над графиката
v.title: Liens

# Подзаглавие под него
v.sub: Number of registered liens and number of liens removed, by quarter.

# Заглавие на таблицата под графиката
v.table: Values by quarter

# Описание на графиката за екранни четци (когато са двата показателя)
v.chartPair: Chart of registered and removed liens by quarter

# Описание на графиката за екранни четци (когато е само един показател; след него се добавя името)
v.chartOne: Chart:

# Пълно име — в легендата под графиката и в подсказката при посочване
v.lien.name: Liens

# Кратко име — в реда за средна стойност
v.lien.short: Liens

# Име на реда в таблицата под графиката
v.lien.row: Liens

# Пълно име — в легендата под графиката и в подсказката при посочване
v.lienDel.name: Removed liens

# Кратко име — в реда за средна стойност
v.lienDel.short: Removed liens

# Име на реда в таблицата под графиката
v.lienDel.row: Removed liens

# Прозорец „!“ — заглавие на параграф 1
v.info1.h: What it shows

# Прозорец „!“ — текст на параграф 1
v.info1.p: How many liens were registered in each office by quarter (blue bars) and how many
    liens were removed in the same quarter (orange bars).

# Прозорец „!“ — заглавие на параграф 2
v.info2.h: What a lien is

# Прозорец „!“ — текст на параграф 2
v.info2.p: A lien (“възбрана”) is a restraint registered against a real-estate property, most
    often linked to the forced collection of debts (at the request of a bailiff, tax
    authorities, a creditor or by court order). Removal means the lien has lapsed, for
    example after the debt was paid. Liens therefore indicate financial pressure on
    owners, not property trading.

# Прозорец „!“ — заглавие на параграф 3
v.info3.h: Source

# Прозорец „!“ — текст на параграф 3
v.info3.p: Registry Agency (Bulgaria), registrations reports by office.

# Прозорец „!“ — заглавие на параграф 4
v.info4.h: Limitations

# Прозорец „!“ — текст на параграф 4
v.info4.p: Removed liens are available from 2009 Q2; before that the column is empty. A removal
    is often of a lien from earlier years, so the difference between the two bars is not
    the exact number of liens in force. The report does not say what debt a lien relates
    to.
