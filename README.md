# Sales Dashboard – Power BI

لوحة معلومات تفاعلية (Interactive Dashboard) مبنية باستخدام **Power BI** لتحليل بيانات المبيعات، تعرض المؤشرات الرئيسية واتجاهات المبيعات وأداء المنتجات والعملاء.




## 📈 المؤشرات الرئيسية (KPIs)

| المؤشر | القيمة |
|---|---|
| Total Cost | 8.46M |
| Total Profit | 1.43M |
| Profit Margin | 14.5% |
| Total Sales | 9.9M |

## 📊 المكونات

### Total Sales by Year & Month
رسم بياني خطي يوضح تطور المبيعات من سنة 2015 حتى 2018.

### Top 10 by Product Sales
أفضل المنتجات من حيث المبيعات:

| المنتج | المبيعات |
|---|---|
| Canon i... | 231.0K |
| GBC Ibi... | 143.5K |
| HON 54... | 100.0K |
| Samsung... | 99.4K |
| Hewlett... | 99.0K |

### Bottom Sales by Product
أقل المنتجات مبيعًا:

| المنتج | المبيعات |
|---|---|
| Avery Hi-... | 15 |
| Boston 19... | 15 |
| Hoover R... | 14 |
| Xerox 1989 | 13 |
| Avery 5 | 12 |

### Top 5 Customers
أفضل 5 عملاء مرتبين تنازليًا حسب إجمالي المبيعات:

| Customer Name | Total Sales | Total Order | Quantity | Discount |
|---|---|---|---|---|
| Adrian Barton | 141,627.40 | 10 | 73 | 4.80 |
| Tamara Chand | 92,482.75 | 5 | 42 | 1.40 |
| Sean Miller | 76,095.84 | 5 | 50 | 3.70 |
| Bill Shonely | 70,965.36 | 5 | 39 | 0.10 |
| Ken Lonsdale | 69,261.15 | 12 | 113 | 5.80 |
| **Total** | **450,432.50** | **37** | **317** | **15.80** |

### Total Sales by Category
مخطط دائري (Donut Chart) لتوزيع المبيعات حسب الفئة:

| Category | Total Sales |
|---|---|
| Technology | 3.49M |
| Office Supplies | 3.23M |
| Furniture | 3.17M |

## 🔍 الفلاتر (Slicers)

- **Year** — تصفية حسب السنة
- **Category** — تصفية حسب فئة المنتج
- **Region** — تصفية حسب المنطقة الجغرافية

## 🛠️ الأدوات المستخدمة

- Microsoft Power BI Desktop
- Power Query لتنظيف وتحويل البيانات
- DAX لإنشاء المقاييس (Measures)

## 📁 هيكل المشروع

```
sales-dashboard-powerbi/
├── README.md
├── dashboard.pbix
├── data/
│   └── sales_data.xlsx
└── images/
    └── dashboard.png
```

 🚀 