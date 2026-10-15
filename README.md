# Task Tracker

Sadə, sürətli və səliqəli tapşırıq izləyicisi. Heç bir kitabxana və ya quraşdırma tələb etmir, yalnız HTML, CSS və vanilla JavaScript ilə yazılıb.

## Xüsusiyyətlər

- Tapşırıq əlavə etmək, tamamlamaq və silmək
- Filtr: **Hamısı / Gözləyən / Tamamlanan**
- Gözləyən və ümumi tapşırıqların sayğacı
- Tamamlanan tapşırıqları bir kliklə təmizləmək
- Məlumatlar brauzerdə (`localStorage`) saxlanılır, səhifə yenilənəndə itmir
- Açıq və tünd rejim dəstəyi (sistem ayarına görə avtomatik)
- Mobil və kompüter üçün uyğun dizayn

## Necə işə salmaq olar

1. Repozitoriyanı klonla:
```bash
   git clone https://github.com/sahsuvarlit-oss/task-tracker.git
```
2. `index.html` faylını brauzerdə aç.

## Canlı demo

https://sahsuvarlit-oss.github.io/task-tracker/

## Layihə strukturu

```
task-tracker/
├── index.html   # səhifənin strukturu
├── style.css    # dizayn və tünd rejim
├── script.js    # tətbiqin məntiqi
└── README.md
```

## İstifadə olunan texnologiyalar

- HTML5
- CSS3 (CSS dəyişənləri, `prefers-color-scheme`)
- JavaScript (ES6+, `localStorage`)

## Gələcək planlar

- [ ] Tapşırığı redaktə etmək
- [ ] Son tarix (deadline) əlavə etmək
- [ ] Sürüşdürərək sıralamaq (drag and drop)
