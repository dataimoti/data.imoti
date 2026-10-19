# SITE TEXTS — ENGLISH
# How to edit: change only the text AFTER the colon. Do not touch the word before the colon (the key).
# Lines starting with # are notes. One line = one text. After editing: Commit + Push origin, then Ctrl+F5.


## General
pageTitle: Property statistics
navAgency: Registry Agency
navBnb: BNB
navContacts: Contacts
comingSoon: This section is coming soon.
allCountry: All Bulgaria
quarter: Quarter
thIndicator: Indicator
unitCount: count
loading: Loading data from the database…
errTitle: The data could not be loaded from the database.
errNoCfg: No Supabase connection: fill in supabaseUrl and anonKey in config.js.

## Buttons and hints
labBar: Bars
labLine: Line
tagOn: Hide values on the chart
tagOff: Show values on the chart
avgOn: Hide the average line
avgOff: Show the average line for the period
avg: Avg
hide: Hide
show: Show
download: Download
dlPng: Image (PNG)
dlXlsx: Table (Excel)
dlCsv: Table (CSV)
dlErr: Download failed. Please try again.
themeToDark: Dark mode
themeToLight: Light mode
langTo: Български
viewOne: One chart with two indicators
viewTwo: Two charts side by side, one indicator each
viewGroup: Chart layout
infoBtn: About the data
officeLabel: Registry office
p1: 1 y
p5: 5 y
p10: 10 y
pAll: All
infoTitle: About the data
sourceUrl: https://www.registryagency.bg/bg/registri/imoten-registar/statistika/
sourceLabel: Statistics page (in Bulgarian)

## CHART 1 — Property sales (prefix s.)
s.title: Property sales
s.sub: Number of registered sales by quarter and the change versus the same quarter of the previous year.
s.table: Values by quarter
s.chartPair: Chart of sales and year-over-year change by quarter
s.chartOne: Chart: 
s.sales.name: Sales
s.sales.short: Sales
s.sales.row: Sales (count)
s.yoy.name: Change vs. the same quarter of the previous year
s.yoy.short: YoY change
s.yoy.row: YoY change (%)
s.info1.h: What it shows
s.info1.p: The number of registered real-estate sales in each registry office, by quarter, and how much higher or lower that is than the same quarter a year earlier.
s.info2.h: How the change is calculated
s.info2.p: (Sales in the quarter − sales in the same quarter of the previous year) ÷ sales in the same quarter of the previous year × 100. We compare Q3 with Q3, not with the previous quarter, so seasonality does not distort the result.
s.info3.h: Source
s.info3.p: Registry Agency (Bulgaria), registrations reports by office.
s.info4.h: Limitations
s.info4.p: The report has no breakdown by property type, so the numbers are not residential-only.

## CHART 2 — Mortgages and share of financed deals (prefix m.)
m.title: Mortgages and share of financed deals
m.sub: Total registered mortgages (contractual + statutory) and what percentage of sales they represent.
m.table: Values by quarter
m.chartPair: Chart of mortgages and the share of financed deals by quarter
m.chartOne: Chart: 
m.mort.name: Total mortgages
m.mort.short: Total mortgages
m.mort.row: Total mortgages
m.mort.desc: Sum of the “Contractual mortgages” and “Statutory mortgages” columns in the Registry Agency report.
m.leg.name: Statutory mortgages
m.leg.row: Statutory mortgages
m.con.name: Contractual mortgages
m.con.row: Contractual mortgages
m.share.name: Share of financed deals
m.share.short: Share of financed deals
m.share.row: % of purchases with a mortgage
m.info1.h: What it shows
m.info1.p: How many mortgages were registered in each office by quarter (blue bars) and what percentage of that quarter's sales they represent (orange bars).
m.info2.h: Total mortgages
m.info2.p: The sum of two columns in the Registry Agency report: Contractual mortgages (darker blue part) + Statutory mortgages (lighter blue part). The two parts are stacked into one bar.
m.info3.h: Share of financed deals
m.info3.p: (Statutory mortgages + Contractual mortgages) ÷ Sales × 100, for the same office and quarter.
m.info4.h: Limitations
m.info4.p: Mortgage data starts in 2006 Q2. This is a ratio of two separate counters in the report, not a tracking of individual deals: one purchase can have more than one mortgage, and a mortgage can be registered without a purchase. The share is therefore an approximate estimate of credit financing.

## CHART 3 — New and deleted mortgages (prefix d.)
d.title: New and deleted mortgages
d.sub: How many new mortgages were registered and how many mortgages were deleted, by quarter.
d.table: Values by quarter
d.chartPair: Chart of new and deleted mortgages by quarter
d.chartOne: Chart: 
d.nw.name: New mortgages
d.nw.short: New mortgages
d.nw.row: New mortgages (total)
d.nw.desc: Sum of the “Contractual mortgages” and “Statutory mortgages” columns in the Registry Agency report.
d.leg.name: Statutory mortgages
d.leg.row: Statutory mortgages
d.con.name: Contractual mortgages
d.con.row: Contractual mortgages
d.del.name: Deleted mortgages
d.del.short: Deleted mortgages
d.del.row: Deleted mortgages
d.info1.h: What it shows
d.info1.p: How many new mortgages were registered in each office by quarter (blue bars) and how many mortgages were deleted in the same quarter (orange bars).
d.info2.h: New mortgages
d.info2.p: The sum of two columns in the Registry Agency report: Contractual mortgages (darker blue part) + Statutory mortgages (lighter blue part). The two parts are stacked into one bar.
d.info3.h: Deleted mortgages
d.info3.p: The value of the “Deleted mortgages” column in the Registry Agency report.
d.info4.h: Limitations
d.info4.p: Mortgage data starts in 2006 Q2. The two bars are separate counters for the quarter: deleted mortgages are often from earlier years, so the difference between them is not the exact net growth of mortgages.
