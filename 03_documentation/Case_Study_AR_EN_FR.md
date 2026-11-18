# Case Study | دراسة حالة | Étude de cas
**Retail Sales Dashboard + Data Cleaning (Power BI)**

---

## 🇬🇧 English

### Retail Sales Dashboard + Data Cleaning Case Study

**Problem**
A UK online gift retailer had about 1.07 million sales lines full of problems: cancelled invoices, negative and zero quantities and prices, non-product lines (postage, fees), duplicate rows, and 23% of rows with no customer ID. Reporting on this data would give wrong revenue and misleading rankings.

**Process**
- Loaded and typed the raw data with Power Query, keeping an untouched copy as proof.
- Moved 19,494 cancelled invoices to a separate returns table instead of deleting them.
- Removed 3,457 stock adjustments, 2,750 zero-price rows, 4,312 non-product lines and 33,669 exact duplicates.
- Kept sales without a customer ID (valid revenue) and excluded them only from customer analysis.
- Built a data model with Date and Country tables, DAX measures and RFM customer segments.
- Documented every step in a cleaning log with row counts.

**Result**
- 1,067,371 raw rows became 1,003,689 clean rows, with every removed row accounted for.
- Total revenue 19.66M, about 40K orders, average order value 497.41, return rate 7.77% (by value).
- Two-page interactive dashboard (Sales Overview + Customer Segments) with Arabic and English titles.
- Insight: 21% of customers (Champions) bring about 68% of revenue, and 709 At Risk customers worth 1.53M can be won back.
- Client report PDF with 5 business recommendations.

**Tools:** Power Query (M), DAX, Power BI, Excel

**Works for your data too:** the same workflow applies to any sales data: Excel exports, POS systems, Shopify and more.

---

## 🇸🇦 العربية

### دراسة حالة: تنظيف بيانات المبيعات ولوحة تحكم في Power BI

**المشكلة**
متجر هدايا بريطاني عبر الإنترنت لديه نحو 1.07 مليون سطر مبيعات مليء بالمشاكل: فواتير ملغاة، كميات وأسعار سالبة أو صفرية، بنود ليست منتجات (شحن ورسوم)، صفوف مكررة، ونحو 23% من الصفوف بلا رقم عميل. أي تقرير على هذه البيانات سيعطي إيرادات خاطئة وترتيباً مضللاً للمنتجات.

**الخطوات**
- تحميل البيانات الخام وضبط أنواعها بـ Power Query مع الاحتفاظ بنسخة أصلية غير معدلة كإثبات.
- نقل 19,494 فاتورة ملغاة إلى جدول مرتجعات منفصل بدل حذفها.
- حذف 3,457 تسوية مخزون و2,750 صفاً بسعر صفري و4,312 بنداً ليس منتجاً و33,669 صفاً مكرراً تماماً.
- الإبقاء على المبيعات التي بلا رقم عميل (لأنها إيراد صحيح) واستبعادها فقط من تحليل العملاء.
- بناء نموذج بيانات بجدولي التاريخ والدول ومقاييس DAX وتقسيم العملاء بطريقة RFM.
- توثيق كل خطوة في سجل تنظيف بعدد الصفوف.

**النتيجة**
- من 1,067,371 صفاً خاماً إلى 1,003,689 صفاً نظيفاً، مع تفسير كل صف محذوف.
- إجمالي الإيرادات 19.66 مليون، ونحو 40 ألف طلب، ومتوسط قيمة الطلب 497.41، ونسبة المرتجعات 7.77% (بالقيمة).
- لوحة تفاعلية من صفحتين (نظرة عامة على المبيعات + شرائح العملاء) بعناوين عربية وإنجليزية.
- رؤية مهمة: 21% من العملاء (الأبطال) يحققون نحو 68% من الإيرادات، و709 عملاء معرّضين للفقد بقيمة 1.53 مليون يمكن استعادتهم.
- تقرير PDF للعميل مع 5 توصيات عملية.

**الأدوات:** Power Query (M) وDAX وPower BI وExcel

**يناسب بياناتك أنت أيضاً:** نفس الطريقة تعمل على أي بيانات مبيعات: ملفات Excel أو نقاط البيع أو Shopify وغيرها.

---

## 🇫🇷 Français

### Étude de cas : nettoyage de données de ventes + tableau de bord Power BI

**Problème**
Un détaillant britannique de cadeaux en ligne avait environ 1,07 million de lignes de ventes pleines d'erreurs : factures annulées, quantités et prix négatifs ou nuls, lignes qui ne sont pas des produits (port, frais), doublons, et 23 % de lignes sans identifiant client. Un rapport sur ces données donnerait un chiffre d'affaires faux et des classements trompeurs.

**Démarche**
- Chargement et typage des données brutes avec Power Query, en gardant une copie intacte comme preuve.
- Déplacement de 19 494 factures annulées vers une table de retours séparée, au lieu de les supprimer.
- Suppression de 3 457 ajustements de stock, 2 750 lignes à prix nul, 4 312 lignes hors produits et 33 669 doublons exacts.
- Conservation des ventes sans identifiant client (revenu valide), exclues seulement de l'analyse clients.
- Création d'un modèle de données (tables Date et Pays), de mesures DAX et d'une segmentation clients RFM.
- Documentation de chaque étape dans un journal de nettoyage avec le nombre de lignes.

**Résultat**
- 1 067 371 lignes brutes sont devenues 1 003 689 lignes propres, avec chaque ligne supprimée justifiée.
- Chiffre d'affaires de 19,66 M, environ 40 000 commandes, panier moyen de 497,41, taux de retour de 7,77 % (en valeur).
- Tableau de bord interactif de 2 pages (Vue des ventes + Segments clients) avec titres en arabe et en anglais.
- Enseignement : 21 % des clients (Champions) apportent environ 68 % du chiffre d'affaires, et 709 clients « À risque » valant 1,53 M peuvent être reconquis.
- Rapport PDF client avec 5 recommandations business.

**Outils :** Power Query (M), DAX, Power BI, Excel

**Ça marche aussi avec vos données :** la même méthode s'applique à toute donnée de ventes : exports Excel, caisses, Shopify, etc.
