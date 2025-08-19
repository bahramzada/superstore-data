# Global Super Store Data Analizi

Bu layihədə **Global Super Store** retail satış datası üzərində geniş analitik və vizual analizlər aparılıb. Layihə Jupyter Notebook (`Global_Super_Store_Dataset.ipynb`) formatındadır və aşağıdakı əsas mərhələləri və nəticələri ehtiva edir:

## Layihənin Məqsədi

Bu dataset retail biznesin satış, mənfəət, müştəri və məhsul göstəricilərini qlobal miqyasda analiz etməyə imkan verir. Məqsəd müxtəlif ölkə, region və məhsul üzrə satış/mənfəət dinamikasını araşdırmaq və biznes strategiyasının optimallaşdırılması üçün əsas göstəriciləri vizuallaşdırmaqdır.

## Əsas Analizlər

- **Datasetin yüklənməsi və ilkin emalı**
- **Statistik göstəricilərin çıxarılması** (orta satış, orta mənfəət, göndərilmə müddəti və s.)
- **Eksik dəyərlərin analizi**
- **Aylara, regionlara və ölkələrə görə satış və mənfəət analizi**
- **Ən çox satılan məhsulların müəyyənləşdirilməsi**
- **Endirim və satış arasındakı əlaqənin statistik qiymətləndirilməsi**
- **Vizualizasiya (matplotlib, seaborn)** – satış və mənfəətin aylara, regionlara və məhsullara görə qrafikləri
- **Prophet ilə Zaman Seriyası Analizi** – satışların və mənfəətin gələcək proqnozlaşdırılması

## Prophet ilə Zaman Seriyası Analizi

Layihənin mühüm hissəsi olaraq, **Facebook Prophet** kitabxanası ilə satış və mənfəət göstəriciləri üzrə zaman seriyası analizi aparılıb. Prophet modeli vasitəsilə:

- İllik, aylıq və həftəlik trendlər aşkar edilib
- Satış və mənfəətin gələcək proqnozu hazırlanıb
- Sezonallıq və bayram effekti araşdırılıb
- Modelin nəticələri vizual şəkildə təqdim olunub

Bu analiz retail biznesin gələcək satış və mənfəət dinamikasını daha öncədən görmək və düzgün strategiya qurmaq üçün imkan yaradır.

## Vizual Nümunələr

Notebookda satış, mənfəət və məhsul populyarlığı üzrə müxtəlif vizuallar mövcuddur. Prophet modelinin proqnoz vizualları, trendlər və sezonallıq qrafikləri də təqdim olunub.

## İstifadə Qaydası

1. `Global_Super_Store_Dataset.ipynb` faylını açın və ardıcıl kod hüceyrələrini işlədin.
2. Əgər sizdə Kaggle API və ya dataset yoxdursa, notebookun əvvəlindəki yükləmə hissəsini özünüzə uyğun dəyişə bilərsiniz.
3. Analiz nəticələrini və vizualları yoxlayın, ehtiyyacınıza uyğun yeni analizlər əlavə edə bilərsiniz.

## Əldə Edilən Nəticələr

- Satış və mənfəət ilin son aylarında ən yüksək olur.
- “Central” regionu satış və mənfəətdə liderdir.
- ABŞ və Avstraliya ən böyük retail bazarına sahibdir.
- Endirim və satış arasında güclü korrelyasiya yoxdur.
- “Staples” adlı məhsul ən çox satılanlar sırasındadır.
- Prophet ilə aparılan analiz satışların və mənfəətin gələcəkdə artacağını göstərir, sezonal dəyişikliklər və bayram effekti nəzərə alınır.

## Quraşdırma və Asılılıqlar

Layihənin işləməsi üçün aşağıdakı Python kitabxanaları lazımdır:
- pandas
- matplotlib
- seaborn
- prophet (zaman seriyası analizi üçün)

```bash
pip install pandas matplotlib seaborn prophet
```

## Müəllif
- Raul Bahramzada

- [https://www.linkedin.com/in/bahramzada/]
- [https://github.com/bahramzada]

---
