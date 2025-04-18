#  WordCloud Scraping News

<h3>Tentang</h3>
Program ini melakukan web scraping berita dari situs online (seperti CNN Indonesia, Kompas, atau Detik), mengekstrak isi artikel, lalu menghasilkan visualisasi WordCloud berdasarkan kata-kata yang paling sering muncul.


<h3>🔧 Fitur</h3>
<p>1. Scraping artikel berita dari situs tertentu.</p>
<p>2. Ekstraksi isi teks berita.</p>
<p>3. Pembersihan teks (stopwords, simbol, angka).</p>
<p>4. Visualisasi dalam bentuk WordCloud.</p>
<p>5. Simpan hasil sebagai gambar PNG.</p>

<h3>🚀 Instalasi</h3>
Install dependencies:

pip install -r requirements.txt

<h3>📦 Requirements</h3>
<p>1. requests</p>
<p>2. beautifulsoup4</p>
<p>3. wordcloud</p>
<p>4. matplotlib</p>
<p>5. nltk (untuk stopwords)</p>

  pip install requests beautifulsoup4 wordcloud matplotlib nltk
  !pip install Sastrawi feedparser wordcloud gradio --quiet
  
<h3>🖼 Contoh Output</h3>

![image](https://github.com/user-attachments/assets/29405571-e588-4ca4-840a-c0330084549a)

![bar_plot](https://github.com/user-attachments/assets/3f097765-f57e-4ad1-8a6d-8ec941249c6d)

![image](https://github.com/user-attachments/assets/cd848935-801c-4364-9bbe-aaca1a6faeea)

<h3>📌 Catatan</h3>

  Website berita memiliki struktur HTML yang berbeda. Pastikan scraper disesuaikan.
  Tidak disarankan scraping dalam jumlah besar tanpa izin dari situs (ikutilah etika web scraping).
