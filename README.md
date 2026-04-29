# 🌍 COVID-19 Global Analytics Dashboard

> Excel + Power BI-ով կառուցված COVID-19 գլոբալ վերլուծության dashboard

---

## 📋 Նախագծի նկարագրություն

Այս նախագիծը վերլուծում է COVID-19 համաճարակի գլոբալ տվյալները՝ օգտագործելով **Microsoft Excel** և **Power BI**։ Dashboard-ը ցույց է տալիս դեպքերի դինամիկան, մահացության և ապաքինման տոկոսները, ինչպես նաև WHO Region-ների և երկրների համեմատական վերլուծությունը։

---

## 📁 Տվյալների աղբյուրը

Տվյալները վերցված են **Kaggle**-ից՝

🔗 [COVID-19 Dataset — imdevskp](https://www.kaggle.com/datasets/imdevskp/corona-virus-report)

### Ֆայլեր

| Ֆայլ | Նկարագրություն | Տողեր |
|------|---------------|-------|
| `country_wise_latest.csv` | Երկրների ամփոփ տվյալներ | 187 |
| `day_wise.csv` | Ամենօրյա գլոբալ տվյալներ (Jan–Jul 2020) | 188 |
| `worldometer_data.csv` | Մանրամասն վիճակագրություն | 209 |
| `full_grouped.csv` | Երկրների ամենօրյա տվյալներ | — |
| `covid_19_clean_complete.csv` | Մաքրված ամբողջական տվյալներ | — |

---

## ⚙️ Օգտագործված գործիքներ

### Microsoft Excel
- **Power Query** — CSV ֆայլերի import, տվյալների մաքրում
- **Conditional Formatting** — վտանգավոր ցուցանիշների ընդգծում
- **Pivot Tables** — WHO Region-ների կտրվածքով ամփոփում
- **Charts** — ժամանակային դինամիկայի գծապատկեր

### Power BI Desktop
- **Data Transformation** — Power Query Editor-ով տվյալների մաքրում և ձևափոխում
- **Card Visual** — KPI ցուցանիշներ
- **Bar Chart** — WHO Region-ների համեմատություն
- **Line Chart** — ժամանակային դինամիկա
- **Scatter Plot** — Mortality vs Recovery Rate
- **Donut Chart** — Deaths by WHO Region
- **Map Visual** — երկրների կտրվածքով քարտեզ
- **Slicer** — WHO Region-ով ինտերակտիվ ֆիլտր
- **Top N Filter** — Top 10 երկրների ցուցադրում
- **Table Visual** — մանրամասն տվյալներ

---

## 📊 Dashboard-ի կառուցվածքը

### Էջ 1 — Global Overview
- 🔢 4 KPI Cards՝ Total Confirmed, Deaths, Recovered, Active
- 📈 Line Chart — Cases Over Time (Jan–Jul 2020)
- 📊 Bar Chart — Cases by WHO Region
- 🗺️ Map — դեպքերը երկրների կտրվածքով
- 🎛️ Slicer — WHO Region ֆիլտր

### Էջ 2 — Regional Analysis
- 🔵 Scatter Plot — Mortality vs Recovery Rate by Country
- 🏆 Bar Chart — Top 10 Countries by Confirmed Cases
- 🍩 Donut Chart — Deaths by WHO Region
- 🎛️ Slicer — WHO Region ֆիլտր

### Էջ 3 — Country Details
- 📋 Table — բոլոր 187 երկրների մանրամասն տվյալներ
- 💀 Card — Avg Mortality Rate
- 💚 Card — Avg Recovery Rate
- 🎛️ Slicer — WHO Region ֆիլտր

---

## 🔍 Հիմնական բացահայտումներ

- **Americas** region-ն ունի դեպքերի ամենամեծ թիվը (52.4% մահերի)
- **US, Brazil, India** — Top 3 երկրներ ըստ դեպքերի
- Գլոբալ **Mortality Rate**՝ ~3.02%
- Գլոբալ **Recovery Rate**՝ ~64.82%
- Դեպքերի կտրուկ աճ՝ Մայիս–Հուլիս 2020

---

## 🚀 Ինչպես օգտագործել

1. Clone կամ Download արա repository-ն
2. CSV ֆայլերը բաց արա Excel-ում
3. `COVID19_Analytics.xlsx` ֆայլը բաց արա Microsoft Excel-ում
4. `Covid_19.pbix` ֆայլը բաց արա Power BI Desktop-ում

---

## 👤 Հեղինակ

**AvagyanArshak** — [GitHub Profile](https://github.com/AvagyanArshak)

