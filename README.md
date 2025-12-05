# 🚀 Ege Yapay Zeka Topluluğu - Web Sitesi Projesi

Bu proje, topluluğumuzun etkinliklerini, blog yazılarını ve üyelerini tanıtmak amacıyla geliştirilen resmi web sitesi projesidir.

## 🛠 Kullanılan Teknolojiler
* **Backend:** .NET Core / ASP.NET
* **Frontend:** (React / Vue / HTML-CSS - *Burayı ekibe göre güncelleyiniz*)
* **Veritabanı:** SQL / PostgreSQL

---

## 📂 Proje Yapısı (Monorepo)
Projemiz tek bir depo (repository) içindedir ancak **iki ana klasöre** ayrılmıştır. Lütfen sadece kendi alanınızda çalışınız.

* **`/backend` Klasörü:** API, Sunucu kodları ve Veritabanı modelleri buradadır.
* **`/frontend` Klasörü:** Arayüz, Tasarım ve Client-side kodlar buradadır.

---

## ⚠️ ALTIN KURALLAR (Mutlaka Okuyun)

1.  **Main Branch Kutsaldır:** `main` branch'ine doğrudan kod atmak (pushlamak) **sistemsel olarak yasaklanmıştır.**
2.  **Branch Açmak Zorunludur:** Her özellik veya düzeltme için yeni bir branch açıp orada çalışmalısınız.
3.  **Klasör Sınırları:** Backend ekibi frontend klasörüne, frontend ekibi backend klasörüne dokunmamalıdır.

---

## 🐢 Adım Adım Geliştirme Rehberi

Projeye kod eklerken karışıklık çıkmaması için aşağıdaki adımları sırasıyla uygulayınız:

### 1. Adım: Projeyi Çekme ve Branch Oluşturma
İşe başlamadan önce mutlaka güncel projeyi çekin ve kendinize yeni bir çalışma dalı (branch) oluşturun.

**Branch İsimlendirme Formatı:** `alan/yapilan-is`
* *Örnekler:* `backend/login-api`, `frontend/navbar-tasarimi`, `fix/hata-duzeltme`

Terminal Komutları:
```bash
# 1. Ana dala geç ve güncel sürümü indir
git checkout main
git pull origin main

# 2. Yeni branch oluştur (İsimlendirmeye dikkat!)
git checkout -b frontend/ana-sayfa-tasarimi
2. Adım: Kodlama
İlgili klasörün içine girin (cd backend veya cd frontend).

Kodlamanızı yapın.

3. Adım: Kaydetme (Commit)
İşiniz bittiğinde dosyaları sahneye alın ve anlaşılır bir mesajla kaydedin.

git add .
git commit -m "Ana sayfa slider tasarımı eklendi"

4. Adım: Gönderme (Push)
Kodları GitHub'a gönderirken main'e değil, kendi branch'inize pushlayın.

# DİKKAT: Buraya kendi branch isminizi yazın
git push origin frontend/ana-sayfa-tasarimi
5. Adım: Onay Alma (Pull Request)
Kodları pushladıktan sonra GitHub proje sayfasına gidin:

Sayfanın üstünde çıkan sarı/yeşil "Compare & pull request" butonuna tıklayın.

Açıklama kısmına ne yaptığınızı kısaca yazın.

Sağ taraftan Reviewers kısmından proje yöneticisini seçin.

Create pull request butonuna basın.

Yönetici kodunuzu inceleyip onayladıktan sonra (Merge), kodlarınız ana projeye dahil olacaktır.
