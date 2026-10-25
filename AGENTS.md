# Project Agent: Food Demand Analysis

##  Project Description
تحليل أداء شركة توصيل وجبات للتنبؤ بالطلب وفهم أنماط المبيعات عبر 145 أسبوعاً. الهدف هو مساعدة مديري المراكز على طلب المواد الغذائية بدقة وتقييم فعالية العروض التسويقية.

##  Data Overview
- `train.csv`: طلبات أسبوعية لكل وجبة في كل مركز (week, center_id, meal_id, num_orders, checkout_price, base_price, emailer_for_promotion, homepage_featured).
- `fulfilment_center_info.csv`: معلومات مراكز التعبئة (center_id, center_type, op_area).
- `meal_info.csv`: معلومات الوجبات (meal_id, category, cuisine).

## 📜 Work Rules
1. يمنع تعديل أو رفع أي ملف من `data/raw` إلى GitHub.
2. عند دمج الجداول (Merge)، يجب طباعة عدد الصفوف قبل وبعد للتأكد من عدم فقدان أي بيانات.
3. في التقارير، يُمنع استخدام كلمة "يسبب" (Causes) بدون إثبات سببي قاطع؛ يجب استخدام "يرتبط بـ" (Correlates with).
4. يجب دائماً ذكر "حدود التحليل" (Limitations) في نهاية أي تقرير (مثل: عدم وجود بيانات عن العطلات الرسمية أو الأحوال الجوية).
