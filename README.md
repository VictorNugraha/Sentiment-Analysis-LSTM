# Analisis Sentimen Berita Harga Emas dengan Model LSTM

Projek ini merupakan project pertama saya sebagai salah satu tim product di Algoritma Data Science Academy. Pada project ini saya melakukan analisis sentimen terhadap berita harga emas dengan menggunakan bantuan <i>machine learning</i>.

Link publikasi: https://rpubs.com/VicNP/sentiment-analysis-lstm

## Tujuan Pembuatan

Tujuan pembuatan projek ini tentu saja untuk mengasah kemampuan saya sebagai seorang Data Scientist untuk mengolah data yang tidak terstruktur (data teks) dengan menggunakan model <i>machine learning</i> yang tradisional maupun dengan <i>deep learning</i>.

Selain untuk tujuan pribadi, implementasi dari analisis sentimen mengenai berita harga emas juga bisa bermanfaat untuk beberapa sisi, seperti:
- Investor emas
- Penjual emas
- Media 

## Input Variable 

Projek ini menggunakan sumber data dari [kaggle](https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-in-commodity-market-gold).

| Variable             	| Detail                                                                           	|
|----------------------	|----------------------------------------------------------------------------------	|
| Dates | Date of news headline |
| URL | URL of news headline |
| News | News headline |
| Price Direction Up | Does the news headline imply price direction up? |
| Price Direction Constant | Does the news headline imply price direction sideways (no change)? |
| rice Direction Down | Does the news headline imply price direction down? |
| Asset Comparision | Are assets being compared? |
| Past Information | Is the news headline talking about past? |
| Future Information | Is the news headline talking about future? |
| Price Sentiment | Price sentiment of Gold commodity based on headline |

## Data Teks Pre-Processing

Text preprocessing adalah suatu proses untuk menyeleksi data text agar menjadi lebih terstruktur lagi dengan melalui serangkaian tahapan. Sedikit tambahan, teks preprocessing merupakan salah satu implementasi dari text mining. Text mining sendiri adalah suatu kegiatan menambang data, di mana data yang biasanya diambil berupa text yang bersumber dari dokumen-dokumen yang memiliki goals untuk mencari kata kunci yang mewakili dari sekumpulan dokumen tersebut sehingga nantinya dapat dilakukan analisis hubungan antara dokumen-dokumen tersebut.

## Machine Learning Model

Untuk menentukan sentiment apa yang terdapat pada berita harga emas, disini saya akan menggunakan model <i>machine learning</i> tradisional yaitu Naive Bayes dan <i>Deep Learning</i> yaitu model <i>Long Short Term Memory (LSTM)</i>. Dari kedua model tersebut, nanti saya akan melihat bagaimana performa model <i>machine learning</i> yang tradisional jika dibandingkan dengan <i>Deep Learning</i>, apakah nantinya memang perlu menggunakan <i>Deep Learning</i> dalam memprediksi data teks atau cukup dengan yang tradsional.
