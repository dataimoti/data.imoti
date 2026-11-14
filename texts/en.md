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
dlXlsx: Table (XLSX)

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
p3: 3 y
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

# ===== BNB =====
bnbMonth: Month
bnbSrcIrLabel: Source: BNB – interest rate statistics (s_ir_all_tables)
bnbSrcIrUrl: https://www.bnb.bg/Statistics/StMonetaryInterestRate/StInterestRate/StIRInterestRate/index.htm
bnbSrcCredLabel: Source: BNB – loans (s_cred_ms_bg)
bnbSrcCredUrl: https://www.bnb.bg/Statistics/StMonetaryInterestRate/StMonetaryStatistics/index.htm

b1.title: Annual percentage rate of charge (APRC) on new loans
b1.sub: Average APRC on new household loans – housing and consumer, by month.
b1.table: Values by month
b1.ul: %
b1.unit: % per year
b1.chartOne: Chart:
b1.chartPair: Chart of APRC on housing and consumer loans by month
b1.hou.name: Housing loans (house purchase)
b1.hou.short: Housing
b1.hou.row: Housing loans, APRC (%)
b1.con.name: Consumer loans
b1.con.short: Consumer
b1.con.row: Consumer loans, APRC (%)
b1.info1.h: What it shows
b1.info1.p: The average annual percentage rate of charge (APRC) on loans to households in euro newly granted during the month. APRC includes interest and loan fees, so it is a fuller measure than the headline interest rate.
b1.info2.h: Source and notes
b1.info2.p: BNB data, monthly. The series may contain breaks (e.g. November 2014 and December 2015) whose cause is not established.

b2.title: New household loans – volumes
b2.sub: Volume of loans to households newly granted during the month, in euro – housing and consumer.
b2.table: Values by month
b2.unit: EUR m per month
b2.ul: EUR m
b2.chartOne: Chart:
b2.chartPair: Chart of new housing and consumer loan volumes by month
b2.hou.name: New housing loans
b2.hou.short: Housing
b2.hou.row: New housing loans (EUR m)
b2.con.name: New consumer loans
b2.con.short: Consumer
b2.con.row: New consumer loans (EUR m)
b2.info1.h: What it shows
b2.info1.p: The total amount of loans to households granted during the month (new business), in EUR million. It shows how active lending is, regardless of the debt already accumulated.
b2.info2.h: Source and notes
b2.info2.p: BNB data, monthly, in euro. Monthly volumes are uneven through the year; use periods of 5+ years or the average line to see the trend.

b3.title: New household loans – annual change
b3.sub: Change in the volume of new loans versus the same month a year earlier, in percent.
b3.table: Values by month
b3.unit: % vs same month a year earlier
b3.ul: %
b3.chartOne: Chart:
b3.chartPair: Chart of the annual change of new housing and consumer loans by month
b3.hou.name: New housing loans: change vs same month a year earlier
b3.hou.short: Housing
b3.hou.row: New housing loans, change (%)
b3.con.name: New consumer loans: change vs same month a year earlier
b3.con.short: Consumer
b3.con.row: New consumer loans, change (%)
b3.info1.h: What it shows
b3.info1.p: How many percent more or fewer loans were granted in the month compared with the same month a year earlier (chart 2). A positive value means growth, a negative one a decline.
b3.info2.h: How it is calculated
b3.info2.p: Calculated in the database from the monthly volumes: (volume this month ÷ volume in the same month last year − 1) × 100. There is no comparison data for 2007. Month-on-same-month changes are volatile; use the average line and longer periods for a clearer picture.

b4.title: Size of the loan portfolio
b4.sub: Outstanding loans at the end of the month: non-financial corporations, households – consumer and housing.
b4.table: Values by month
b4.unit: EUR m, outstanding at month end
b4.ul: EUR m
b4.chartOne: Chart:
b4.chartPair: Chart of the size of the loan portfolio by month
b4.nfc.name: Non-financial corporations – loans
b4.nfc.short: Non-financial corporations
b4.nfc.row: Non-financial corporations, loans (EUR m)
b4.con.name: Households – consumer loans
b4.con.short: Consumer
b4.con.row: Households, consumer loans (EUR m)
b4.hou.name: Households – housing loans
b4.hou.short: Housing
b4.hou.row: Households, housing loans (EUR m)
b4.info1.h: What it shows
b4.info1.p: How much outstanding credit there is at the end of each month – in total for non-financial corporations and separately consumer and housing loans to households. It includes performing and bad (restructured) loans.
b4.info2.h: Source and notes
b4.info2.p: BNB data (table "Loans to non-financial corporations, financial corporations, households and NPISH, residents of Bulgaria", in EUR thousand). Shown here in EUR million; stored in EUR thousand in the database. Corporate loans exclude overdrafts. The series contains breaks in late 2014 and 2015 whose cause is not established.

b5.title: Deposit interest rates
b5.sub: Average interest rate on deposits: households (over 3 to 6 months) and the weighted average for households and corporations (over 1 day to 2 years).
b5.table: Values by month
b5.unit: % per year
b5.ul: %
b5.chartOne: Chart:
b5.chartPair: Chart of deposit interest rates by month
b5.hh36.name: Households – deposits over 3 to 6 months
b5.hh36.short: Households, 3–6 mo.
b5.hh36.row: Households, deposits over 3 to 6 months (%)
b5.w.name: Households and corporations – weighted average rate, over 1 day to 2 years
b5.w.short: Weighted average, up to 2 y
b5.w.row: Weighted average rate, households and corporations, over 1 day to 2 years (%)
b5.info1.h: What it shows
b5.info1.p: How much interest banks pay on deposits. The first line is for household deposits with a maturity of over 3 to 6 months. The second is combined for households and non-financial corporations, with a maturity of over 1 day to 2 years.
b5.info2.h: How it is calculated
b5.info2.p: The rates refer to outstanding amounts, i.e. all existing deposits, not only new ones. The weighted average is calculated in the database: (corporate rate × corporate volume + household rate × household volume) ÷ total volume. The sector with more money weighs more.
