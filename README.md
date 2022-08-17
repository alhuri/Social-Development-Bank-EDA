# Social-Development-Bank-EDA
View the report [here](https://alhuri.github.io/Social-Development-Bank-EDA/gov_banking_eda.html)

## About Social Development Bank

“The Bank is considered to be one of the main government pillar for economical and social development funding to the  citizens in Saudi Arabia. SDB focus's  in providing social financing products and business solutions to the low income citizens, and creating awareness in financial planning & saving , as well as funding freelancers, micro, startup , and small businesses  in way to enable them to contribute effectively to the economic growth of  the country. 
The objectives have been verified as the following:

- To provide free of interest loans for freelancers , micro , startup and small business  to encourage them to run their own businesses independently.
- To provide free of interest  Social Loans for low income citizens , in order to help them overcome their financial difficulties.
- To encourage savings for individuals and institutions in the Kingdom, and to find the appropriate tools to achieve this goal.

The Bank has 24 branches in different regions of the Kingdom of Saudi Arabia to deliver services efficiently to its citizens.”

### Scenario:

Ministry of Finance Vision Realization Office (VRO) have asked SDB to show how they are achieving their goals in order to increase or decrease budget/funding.

Reading about the Social Development Bank Objectives and Vision ([In relation to Vision 2030](https://www.sdb.gov.sa/en-us/about-us/bank_vision_2030)). We completed a thorough analysis for the SDB bank loans the past 5 year (since the initiation of Vision 2030). This is to investigate how the direction of SDB lending practices have changed since establishment.

## Social Development Bank 2017-2022
Social Development Bank dataset is an open source data provided by the Open Data portal of Saudi Arabia initiative. The social funding products are designed to target an important community segment in the Saudi Arabia, the underprivileged citizens, offering them an opportunity to obtain simple and easy loans which enable them to meet necessary obligations

### Get the data here
The data comes from [Social Development Bank](https://data.gov.sa/Data/en/organization/social_development_bank). 

### Data Dictionary



|التعريف |	المتغير |
|:---------|:-----------|
مدينة العميل الذي صرف له القرض	|المدينة
نوع القرض (افراد، اعمال، نقل)|	نوع التمويل
نوع القرض المصروف للعميل	|المنتج
القطاع الذي يعمل فيه العميل|	قطاع العميل
المبلغ المقدم كقرض للعميل|	قيمة التمويل
مبلغ سداد التمويل الشهري	|قيمة القسط
الشهر الذي صرف فيه التمويل|	تاريخ الصرف
ذكر او انثى	|جنس العميل
المرحلة العمرية التي ينتمي لها العميل (شباب، بالغ في منتصف العمر، كبار سن، الخ)	|الفئة العمرية
الحالة الزواجية أو الحالة المدنية للشخص	|الحالة الاجتماعية
هل العميل من ذوي الاحتياجات الخاصة (نعم، لا)|	احتياجات خاصة
العدد التقريبي لأفراد اسرة العميل	|عدد افراد الاسرة
هل القرض ادخاري؟ (نعم، لا)	|قرض ادخاري
الدخل التقريبي الشهري للعميل	|قيمة الدخل
تصنيف الدخل الى مجموعات ما بين (ضعيف، متوسط، مرتفع، الخ)	|نوع الدخل
السنة التي صرف فيها التمويل	|السنة

* *For the english description of data refer to the presentation file*


## Content 

```bash
./
│   README.md
│   
└───data/
│   │   gov_banking_data.csv
│   
└───presentation/
│   │   presentation.pptx
│   
└───src/
    │   preprocessing_concatenation.ipynb
    │   gov_banking_eda.ipynb
```

## Used Libraries
`pandas` 
`numpy` 
`matplotlib`
`seaborn`
`arabic_reshaper`
`bidi.algorithm`
`plotly`

