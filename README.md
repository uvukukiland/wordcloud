#  WordCloud Scraping News

<h3>Tentang</h3>
Program ini melakukan web scraping berita dari situs online (seperti CNN Indonesia, Kompas, atau Detik), mengekstrak isi artikel, lalu menghasilkan visualisasi WordCloud berdasarkan kata-kata yang paling sering muncul.


<h3>🔧 Fitur</h3>
1. Scraping artikel berita dari situs tertentu.
2. Ekstraksi isi teks berita.
3. Pembersihan teks (stopwords, simbol, angka).
4. Visualisasi dalam bentuk WordCloud.
5. Simpan hasil sebagai gambar PNG.

<h3>🚀 Instalasi</h3>

  Clone repositori ini:

git clone https://github.com/namamu/wordcloud-news-scraper.git
cd wordcloud-news-scraper

Install dependencies:

pip install -r requirements.txt

<h3>📦 Requirements <h3>

  1. requests
  2. beautifulsoup4
  3. wordcloud
  4. matplotlib
  5. nltk (untuk stopwords)

pip install requests beautifulsoup4 wordcloud matplotlib nltk

🛠 Cara Pakai

python scraper.py

Atau jika ingin scraping dari URL tertentu:

python scraper.py --url "https://www.detik.com/..."

🖼 Contoh Output

Setelah scraping dan memproses data, program akan menghasilkan file wordcloud.png seperti berikut:

📁 Struktur Folder

wordcloud-news-scraper/
│
├── scraper.py           # File utama scraping dan generate wordcloud
├── utils.py             # Fungsi bantu untuk cleaning dan text processing
├── requirements.txt     # Library yang dibutuhkan
├── output/
│   └── wordcloud.png    # Output file
└── README.md

📌 Catatan

  Website berita memiliki struktur HTML yang berbeda. Pastikan scraper disesuaikan.
  Tidak disarankan scraping dalam jumlah besar tanpa izin dari situs (ikutilah etika web scraping).
