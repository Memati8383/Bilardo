# 🎱 Billiards Master - Pro Edition

Billiards Master, modern web teknolojileri ile geliştirilmiş, hem masaüstü hem de mobil cihazlarda oynanabilen premium bir 8 top bilardo oyunudur. Gerçekçi fizik motoru ve şık arayüzü ile tarayıcınızda keyifli bir bilardo deneyimi sunar.

## 🌟 Özellikler

- **Gerçekçi Fizik Motoru:** Top çarpışmaları, sürtünme ve bant sekmeleri fizik kurallarına uygun olarak simüle edilmiştir.
- **Gelişmiş Nişan Sistemi:** Vuruş öncesi topun gideceği yönü ve olası çarpışmaları gösteren ışın izleme (raycasting) tabanlı rehber çizgiler.
- **Duyarlı Tasarım (Responsive):** Hem bilgisayarınızda hem de telefonunuzda sorunsuz çalışır. Dokunmatik ekran desteği mevcuttur.
- **Modern UI:** Tailwind CSS ile tasarlanmış, cam efekti (glassmorphism) ve yumuşak animasyonlar içeren şık arayüz.
- **Oyun Durumu Takibi:** Alt kısımdaki tepsi (tray) üzerinden deliğe giren topları ve sıradaki topları takip edebilirsiniz.
- **Ses ve Görsel Efektler:** Vuruş gücü göstergesi ve dinamik durum mesajları ("Harika!", "Faul!" vb.).

## 🎮 Nasıl Oynanır?

1.  **Oyunu Başlat:** `index.html` dosyasını tarayıcınızda açın ve "OYUNA BAŞLA" butonuna tıklayın.
2.  **Nişan Al:** Beyaz topa (Cue Ball) tıklayın/dokunun.
3.  **Vuruş Gücünü Ayarla:** Tıkladıktan sonra geriye doğru çekerek vuruş hızını ayarlayın (çekme mesafesi gücü belirler).
4.  **Vur:** Parmağınızı veya mouse tuşunu bıraktığınızda vuruş gerçekleşir.
5.  **Kurallar:**
    - Amacınız renkli topları deliklere sokmaktır.
    - Beyaz top deliğe girerse "Faul" olur ve skorunuzdan düşülür.
    - Siyah top (8 numara) en son deliğe sokulmalıdır. Erken sokarsanız oyunu kaybedersiniz.

## 🛠️ Teknolojiler

Bu proje aşağıdaki teknolojiler kullanılarak geliştirilmiştir:

- **HTML5 Canvas API:** Oyun içi tüm grafik çizimleri ve animasyonlar için.
- **Vanilla JavaScript (ES6+):** Tüm oyun mantığı, fizik motoru ve etkileşimler için (harici kütüphane bağımlılığı olmadan).
- **Tailwind CSS (CDN):** Hızlı ve modern arayüz tasarımı için.
- **Google Fonts (Inter):** Tipografi için.

## 📂 Kurulum

Herhangi bir sunucu kurulumuna gerek yoktur. Proje klasöründeki `index.html` dosyasına çift tıklayarak varsayılan web tarayıcınızda (Chrome, Edge, Safari vb.) hemen oynamaya başlayabilirsiniz.

---

_İyi eğlenceler!_
