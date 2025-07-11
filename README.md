# **Website Redesign: Asosiasi Energi Surya Indonesia (AESI)**

## **Deskripsi Proyek**

Proyek ini adalah implementasi redesign total untuk website statis Asosiasi Energi Surya Indonesia (AESI). Tujuannya adalah untuk memodernisasi antarmuka pengguna (UI) dan pengalaman pengguna (UX), memberikan tampilan yang lebih **elegan, profesional, dan futuristik**.

Fokus utama adalah pada perapian struktur kode, adopsi praktik pengembangan web modern, dan penciptaan desain yang bersih serta responsif di berbagai perangkat.

## **Pratinjau Desain**

*(Tips: Setelah Anda mengunggah proyek ini ke GitHub Pages, ganti `URL_WEBSITE_ANDA` di bawah ini dengan link yang aktif)*

**Live Demo:** [**project-aesi.github.io**](https://www.google.com/search?q=URL_WEBSITE_ANDA)

*(Screenshot di atas adalah representasi desain. Anda bisa menggantinya dengan screenshot hasil akhir proyek Anda)*

## **Fitur Utama & Perubahan Teknis**

  * **Desain UI/UX Modern:** Antarmuka yang didesain ulang dari awal dengan pendekatan minimalis dan futuristik.
  * **Sepenuhnya Responsif:** Tampilan yang optimal di perangkat desktop, tablet, dan mobile.
  * **Struktur Proyek Terorganisir:** Penataan file dan folder yang rapi (`assets`, `css`, `images`) untuk kemudahan pengelolaan.
  * **Kode yang Direfaktor:** Kode HTML dan CSS yang lebih bersih, semantik, dan mudah dibaca.
  * **Tipografi Profesional:** Penggunaan Google Fonts (Oswald & Outfit) untuk keterbacaan dan estetika modern.
  * **CSS Modern:** Menggunakan CSS Variables (Custom Properties) untuk kemudahan kustomisasi tema dan *styling*.

## **Teknologi yang Digunakan**

Proyek ini dibangun murni menggunakan teknologi web fundamental tanpa *framework* eksternal untuk menjaga keringanan dan kecepatan.

  * **HTML5:** Untuk struktur konten yang semantik.
  * **CSS3:** Untuk styling, layout (Flexbox & Grid), dan responsivitas.
  * **Google Fonts:** Untuk memuat *font* web (`Oswald` dan `Outfit`).

## **Struktur Folder Proyek**

Struktur folder proyek diatur untuk memisahkan aset dari logika markup, sesuai dengan praktik terbaik pengembangan web.

```
/project-aesi/
│
├── assets/
│   ├── css/
│   │   └── main.css         # File styling utama
│   │
│   └── images/
│       ├── hero-background.png # Gambar utama
│       └── logo-aesi.png       # Logo asosiasi
│
├── index.html               # File markup utama
└── README.md                # Dokumentasi teknis proyek (file ini)
```

## **Instalasi dan Menjalankan Proyek**

Karena ini adalah proyek website statis, Anda tidak memerlukan instalasi *dependency* yang kompleks.

1.  **Clone Repositori**
    Gunakan perintah berikut untuk mengunduh proyek ke mesin lokal Anda:

    ```bash
    git clone https://github.com/farrosfr/project-aesi.git
    ```

    *(Jangan lupa ganti `farrosfr/project-aesi` dengan username dan nama repositori Anda)*

2.  **Buka Proyek**
    Navigasikan ke direktori proyek dan buka file `index.html` menggunakan browser pilihan Anda.

    ```bash
    cd project-aesi
    ```

    Cukup klik dua kali pada file `index.html`.

    **Rekomendasi:** Untuk pengalaman pengembangan terbaik (terutama untuk *hot-reloading*), gunakan ekstensi **Live Server** di Visual Studio Code.

## **Filosofi Desain**

Desain ini dibangun di atas tiga pilar utama:

1.  **Palet Warna Tegas & Profesional**

      * `--primary-color: #00992E` (Hijau AESI): Melambangkan energi bersih, pertumbuhan, dan identitas utama asosiasi.
      * `--secondary-color: #FF8A00` (Oranye Aksen): Memberikan kontras, menarik perhatian ke elemen interaktif (CTA), dan melambangkan energi matahari.
      * `--dark-color: #1a1a1a`: Digunakan untuk teks dan latar belakang gelap (footer) untuk menciptakan kesan elegan dan fokus.

2.  **Tipografi Modern & Jelas**

      * **Oswald:** Digunakan untuk *heading*. Karakternya yang sedikit padat dan tegas memberikan nuansa modern dan kuat, cocok untuk judul.
      * **Outfit:** Dipilih untuk *body text* karena geometrinya yang bersih, sehingga sangat mudah dibaca dalam ukuran kecil dan memberikan kesan futuristik.

3.  **Tata Letak Bersih & Terstruktur**

      * **Whitespace:** Penggunaan ruang kosong yang melimpah untuk "memberi napas" pada konten, meningkatkan fokus, dan menciptakan nuansa premium.
      * **Layout Grid:** Pemanfaatan *CSS Grid* dan *Flexbox* untuk menyusun konten secara simetris dan responsif.
      * **Card-based UI:** Konten seperti program dan berita disajikan dalam format kartu untuk memisahkan informasi secara visual dan membuatnya mudah dicerna.

## **Kustomisasi**

Desain ini sangat mudah untuk dikustomisasi. Cukup ubah nilai variabel di bagian `:root` pada file `assets/css/main.css`.

```css
/* assets/css/main.css */

:root {
    --primary-color: #00992E; /* Ganti warna hijau utama */
    --secondary-color: #FF8A00; /* Ganti warna oranye aksen */
    --dark-color: #1a1a1a;
    --light-color: #f8f9fa;
    --text-color: #333;
    --font-heading: 'Oswald', sans-serif; /* Ganti font judul */
    --font-body: 'Outfit', sans-serif;   /* Ganti font teks */
    --border-radius: 8px; /* Atur lengkungan sudut */
}
```

-----

### **Author**

Didesain dan dikembangkan oleh **farrosfr**.

> *"May the eyes of cowards never sleep."* - Khalid bin Walid
