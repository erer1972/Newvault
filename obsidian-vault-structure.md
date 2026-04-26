# Obsidian Vault Yapısı ve Organizasyon Rehberi

## 📁 Temel Klasör Yapısı

```
Newvault/
├── 00_Inbox/                    # Hızlı not almak için (haftalık inceleme)
├── 01_Daily/                    # Günlük notlar (dailies)
├── 02_Projects/                 # Proje yönetimi
├── 03_Work/                     # İş ve araştırma dosyaları
├── 04_Personal/                 # Kişisel bilgiler
├── 05_Knowledge/                # Bilgi tabanı (MOC'lar, referans)
├── 06_Archive/                  # Tamamlanan projeler
├── 07_Templates/                # Not şablonları
├── 08_Attachments/              # Görseller, PDF'ler
└── _Meta/                       # Vault ayarları, indeks
```

---

## 📝 Her Klasörün Amacı

### **00_Inbox** (Hızlı Giriş)
- Hızlı not almak, tasnif etmekten kaçınma
- Haftalık inceleme & arşivleme
- Format: `inbox_YYYY-MM-DD.md` veya boş başlıklar

**Örnek Not:**
```
# Hızlı Not - 2025-04-26

- [ ] Foseptik temizliği araştır
- [ ] Bahçe yosunu çözümü bul
- Yeni web projesi fikri...
```

---

### **01_Daily** (Günlük Notlar)
- Obsidian Daily Notes plugin'iyle entegre
- Format: `YYYY-MM-DD.md` (otomatik)
- Günlük aktivite, düşünceler, müşahatlar

**Önerilen Template:**
```markdown
# 2025-04-26

## Bugün
- Yapılacaklar
- Notlar

## Öğrenilen
- Yeni bilgi

## Yansıtma
- Ne gitti iyi? Ne geliştirilebilir?
```

---

### **02_Projects** (Proje Yönetimi)
Yapı:
```
02_Projects/
├── Web Development/
│   ├── Project_WebApp_2025.md
│   └── Subfolders for components
├── Automotive Research/
│   ├── Toyota_Boshoku_Study.md
│   └── Supplier_Analysis.md
├── Home & Garden/
│   ├── Garden_Moss_Solution.md
│   └── Septic_Tank_Maintenance.md
```

**Proje Not Template:**
```markdown
# [Proje Adı]

## Meta
- Status: 🔄 Devam Ediyor / ✅ Tamamlandı / 🔴 Durduruldu
- Start Date: YYYY-MM-DD
- Deadline: YYYY-MM-DD
- Tags: #project #work #urgent

## Hedef
Proje hedefini net olarak yaz

## Aşamalar
- [ ] Aşama 1
- [ ] Aşama 2
- [ ] Aşama 3

## Kaynaklar
- [[Related_Note_1]]
- [[Related_Note_2]]
- [External Link](url)

## Progress
Güncellemeler ve ilerleme
```

---

### **03_Work** (İş & Araştırma)
```
03_Work/
├── Automotive_Industry/
│   ├── Tier1_Suppliers.md
│   ├── Supply_Chain_Map.md
│   └── European_Benchmarks.md
├── Research_Topics/
├── Meeting_Notes/
└── Resources/
```

---

### **04_Personal** (Kişisel Alan)
```
04_Personal/
├── Health & Wellness/
├── Hobbies/
│   ├── Cooking_Recipes.md
│   └── Web_Design_Ideas.md
├── Travel/
│   ├── Poland_Trip_2025.md
│   └── Belgium_Locations.md
├── Finance/
│   └── BES_Portfolio.md
└── Home Management/
    ├── Garden_Log.md
    └── Home_Maintenance.md
```

---

### **05_Knowledge** (Bilgi Tabanı - MOC'lar)
**MOC** = Map of Content (içerik haritası)

```
05_Knowledge/
├── MOC_Technology.md          # Tech başlıkları için index
├── MOC_Lifestyle.md           # Yaşam tarzı başlıkları
├── MOC_Business.md            # İş/araştırma index
├── Evergreen_Notes/           # Kalıcı notlar
│   ├── How_to_Learn.md
│   ├── Productivity_Systems.md
│   └── Growth_Mindset.md
└── Reference/
    ├── Tools_and_Software.md
    └── Writing_Tips.md
```

**MOC Örneği:**
```markdown
# MOC - Teknoloji

## Frontend
- [[React Fundamentals]]
- [[Tailwind CSS]]
- [[Web Components]]

## Backend
- [[Node.js Best Practices]]
- [[Database Design]]

## DevOps
- [[Docker Containers]]
- [[Linux Commands]]
```

---

### **06_Archive** (Arşiv)
- Tamamlanan projeler
- Eski bilgiler
- Yapı: `Archive_[Date]_ProjectName.md`

---

### **07_Templates** (Şablonlar)
```
07_Templates/
├── Daily_Note_Template.md
├── Project_Template.md
├── Meeting_Notes_Template.md
├── Research_Template.md
└── Book_Review_Template.md
```

**Obsidian'da Kullanım:**
- Hotkey ata: `Ctrl+T` → Template
- Template klasörü ayarlar → Options → Files & Links

---

### **08_Attachments** (Medya)
```
08_Attachments/
├── Screenshots/
├── Photos/
├── PDFs/
└── Documents/
```

**Not:** Obsidian ayarlarında:
`Files & Links → Attachment folder location: 08_Attachments`

---

### **_Meta** (Vault Metadata)
```
_Meta/
├── Index.md              # Vault'un ana girişi
├── PKM_System.md         # Sistem açıklaması
├── Plugins_Installed.md  # Yüklü plugin listesi
├── Daily_Dashboard.md    # Hızlı erişim panosu
└── Backlinks_Graph.md    # Bağlantı haritası
```

---

## 🏷️ Tagging Sistemi

**Temel Etiketler:**
```
#project        → Proje Not
#work          → İş ile ilgili
#personal      → Kişisel
#urgent        → Acil
#idea          → Fikir / Beyin fırtınası
#research      → Araştırma
#tutorial      → Rehber
#favorite      → Favori / Önemli
#review        → İnceleme gereken
#archived      → Arşivlenmiş
```

**Alt-etiketler (Özel Alanlar):**
```
#automotive/suppliers
#home/garden
#cooking/recipes
#travel/destinations
#tech/frontend
```

---

## 📌 Obsidian Plugin Önerileri

### Essential Plugins:
1. **Daily Notes** - Günlük otomatik notlar
2. **Templates** - Şablon oluşturma
3. **Dataview** - Dinamik içerik (veritabanı gibi)
4. **Backlinks** - Bağlantı yönetimi
5. **Graph View** - Görsel harita

### İleri Seviye:
6. **Kanban** - Proje tahtası
7. **Excalidraw** - Diyagram çizimi
8. **Calendar** - Takvim görünümü
9. **Tag Wrangler** - Etiket yönetimi
10. **Quick Switcher** - Hızlı not bulma

### Community Plugins (Opsiyonel):
- **Obsidian Git** - Vault sürüm kontrolü
- **Metadata Menu** - Gelişmiş metadata
- **Natural Language Dates** - Doğal dil tarihleri

---

## 🔗 Linking Best Practices

### İç Bağlantı Formatı:
```markdown
[[Note_Name]]              # Basit bağlantı
[[Note_Name|Custom Text]]  # Özel metin
[[Note#Section]]           # Başlığa bağlantı
[[Note|Alias]]             # Takma ad
```

### Örnek:
```markdown
Proje hakkında daha fazla bilgi için [[02_Projects/Project_Name]] bak.
Benzer bilgi: [[MOC_Technology#Frontend]]
```

---

## 📊 Dashboard Yapısı (_Meta/Daily_Dashboard.md)

```markdown
# 📊 Günlük Dashboard

## 🔴 Acil Görevler
- Dataview sorgusu: `task` filtresi

## 📌 Devam Eden Projeler
- Tüm `#project` ve `status:🔄` notları

## 📚 Son Eklenen Notlar
- Son 5 not

## 📊 Grafik
- Obsidian Graph View
```

---

## 💾 Yedekleme & Senkronizasyon

### Önerilen Çözümler:
1. **Obsidian Sync** (Ücretli)
2. **Git + GitHub** (Ücretsiz)
3. **Synology NAS** (Senin sisteminde!)
4. **Cloud Storage** (Drive, OneDrive)

### Senin Durumunda (NAS var):
```
Newvault/ → Synology NAS'ına SMB mount
         → GitHub'a Git push
         → Harici SSD yedek
```

---

## 🎯 İlk 7 Günlük Kurulum Planı

| Gün | Görev |
|-----|-------|
| **1-2** | Klasör yapısını oluştur, temel ayarlar |
| **3-4** | Templates ve plugin'leri kur |
| **5-6** | MOC'lar oluştur ve ilk notları ekle |
| **7** | Dashboard, git, backup sistemini ayarla |

---

## 📖 Örnek Not Yapısı

### Proje Notu (Turkish Cuisine Website):
```markdown
# Turkish Cuisine Website Project

## Meta
- Status: 🔄 Development
- Type: #project #web
- Start: 2025-01-15
- Deadline: 2025-06-30
- Related: [[03_Work/Web_Development]]

## Objective
Create bilingual Turkish-English cookbook website with regional chapters

## Features
- [ ] Homepage design
- [ ] Recipe database
- [ ] Search functionality
- [ ] Photo gallery
- [ ] User authentication

## Tech Stack
- Frontend: [[React]], [[Tailwind CSS]]
- Backend: [[Node.js]]
- Database: [[MongoDB]]

## Resources
- [Turkish Recipes Reference](link)
- [[04_Personal/Hobbies/Cooking_Recipes]]

## Progress Log
- 2025-04-26: Başladı, temel yapı oluşturuldu
```

---

## 🚀 Hızlı Start Checklist

- [ ] Klasörleri oluştur
- [ ] Daily Notes plugin kur
- [ ] Templates plugin kur
- [ ] İlk 3 MOC oluştur
- [ ] Tagging sistemi dokümante et
- [ ] Git/Backup kur
- [ ] Daily Dashboard oluştur
- [ ] Ilk notları ekle

---

## 📞 Ihtiyacın Olursa

Şu şeyleri istersen daha detaylı rehber yazabilirim:
- Specific plugin setup guides
- Advanced Dataview queries
- Git workflow nasıl kurulan
- PARA method uyarlama
- Zettelkasten sistemi
- GTD (Getting Things Done) entegrasyonu

**Hazır mısın başlamaya?** 🚀
