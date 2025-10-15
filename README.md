# AIDEA-Overfitters

# Odak Koçu – ADHD Hastaları İçin Yapay Zeka Destekli Kişisel Odak ve Pomodoro Asistanı

Bu proje, ADHD (Dikkat Eksikliği ve Hiperaktivite Bozukluğu) hastalarının odaklanma ve zaman yönetimini iyileştirmek için Pomodoro Tekniği'ni kullanan bir verimlilik aracıdır. Yapay zeka destekli bir sistemle kişiselleştirilmiş rehberlik sunmayı ve LLM (Büyük Dil Modeli) entegrasyonu ile motivasyonel öneriler sağlamayı hedefler.

## Proje Ekibi
- **Takım Adı**: Overfitters
- **Takım Üyeleri**: Canan Erva Aydın, Elif Beraa Çığrıkçı, Mustafa Furkan Yılmaz, Nuran Er, Tuba Çalcı
- **Mentör**: Esra Tunçer

## Proje Özeti
Proje, hiperaktif bozukluğu olan hastaların dikkatlerini artırmaya yönelik özelleştirilmiş bir Pomodoro asistanı geliştirmeyi amaçlar. LLM entegrasyonu ile bireysel profiller oluşturularak verimlilik optimize edilecek ve kullanıcılara motivasyonel rehberlik sunulacaktır.

## Proje Başlangıç Yapısı
Projenin başlangıç yapısı aşağıdaki gibi organize edilmiştir:

```
OdakKocu-Pomodoro/
├── README.md              # Proje açıklaması, ekip bilgileri ve zaman çizelgesi
├── requirements.txt       # Proje için gerekli Python kütüphaneleri
├── .gitignore             # Git tarafından takip edilmeyecek dosyalar
├── docs/                  # Dokümantasyon dosyaları
│   └── proje_raporu.pdf   # 1. hafta için hazırlanan proje raporu
├── src/                   # Kaynak kodlarının ana dizini
│   ├── app/               # Arka uç ve uygulama mantığı
│   │   └── __init__.py    # Flask uygulamasının başlangıç dosyası
│   ├── static/            # Statik dosyalar (CSS, JS, resimler)
│   │   ├── css/           # Stil dosyaları
│   │   └── js/            # JavaScript dosyaları
│   └── templates/         # HTML şablonları
│       └── base.html      # Temel şablon dosyası
├── data/                  # Veri dosyaları (dummy data ile başlanacak)
│   └── dummy_data.json    # Başlangıç için örnek veri seti
└── notes/                 # Toplantı notları ve planlamalar
    └── week1_notes.md     # 1. hafta toplantı notları
```

Bu yapı, projenin geliştirilmesine temel oluşturur ve ilerleyen haftalarda genişletilecektir.

## Kullanılacak Yöntem ve Teknolojiler
- **Yöntem**: Kullanıcı girdilerine dayalı bireysel odak profilleri oluşturmak için yapay zeka tahmini modelleri kullanılacak. LLM, motivasyonel mesajlar ve görev önerileri için entegre edilecek. Başlangıçta dummy data ile test edilecek.
- **Teknolojiler**:
  - **Arka Uç**: Python ile Flask, flask-pymongo, Werkzeug
  - **Ön Uç**: HTML, CSS, JavaScript
  - **Veritabanı**: MongoDB
  - **Yapay Zeka/LLM**: xAI API veya benzeri servis

## Proje Zaman Çizelgesi
- **1. Hafta (15-21 Ekim 2025)**: Gereksinim analizi, rapor hazırlığı ve repo kurulumu
- **2. Hafta (22-28 Ekim 2025)**: Arka uç geliştirme ve veritabanı kurulumu
- **3. Hafta (29 Ekim - 4 Kasım 2025)**: Ön uç tasarımı ve entegrasyonu
- **4. Hafta (5 Kasım 2025)**: Prototip testleri ve sunum
