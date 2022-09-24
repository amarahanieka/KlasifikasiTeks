# Klasifikasi Teks

Alifah Rahmatika Basyasya (13519053)  
J. Amara Hanieka (13519082)  
Giovani Anggasta (13519155)  
Clarisa Natalia Edelin (13519213)  

[Link PPT penjelasan](https://docs.google.com/presentation/d/1ZYhKWCm13C_WcUi8udH69YBbbhy1m6hWKjU-FAV_S14/edit?usp=sharing)

Seluruh notebook dapat dijalankan menggunakan Google Colab/Jupyter Notebook.

## Shallow Machine Learning menggunakan SVM
Support Vector Machine (SVM) merupakan algoritma pembelajaran mesin yang bertujuan untuk menemukan hyperplane di dalam sebuah N dimensi, dimana N merupakan banyak fitur, yang dapat digunakan untuk mengelompokkan data. Dalam proses klasifikasinya, SVM dipengaruhi oleh beberapa parameter, yaitu nilai C, nilai gamma, dan jenis kernel. Untuk mendapatkan kombinasi parameter terbaik dapat dilakukan proses hypertune parameter dengan menggunakan model pencarian seperti GridSearch.

## Algoritma Deep Learning menggunakan Word2Vec
Word2Vec merupakan salah satu metode word embedding yang berguna untuk merepresentasikan kata menjadi sebuah vektor dengan panjang N. Vektor yang dibentuk oleh Word2Vec tidak hanya merepresentasikan kata secara syntax tetapi juga secara makna atau semantik. Word2Vec menggunakan neural network untuk membentuk vektor kata tersebut. Dibutuhkan 3 buah layer untuk membentuk vektor kata tersebut yaitu input layer, hidden layer (projection), dan output layer. Word2Vec menggunakan 2 arsitektur neural network yaitu Skip-Gram dan Continuous Bag of Word (CBOW).

## Fine Tuning BERT
Bidirectional Encoder Representations from Transformers (BERT)  adalah salah satu teknik pembelajaran mesin untuk natural language processing yang dikembangkan oleh Google. Model BERT memanfaatkan data dari BookCorpus dan Wikipedia bahasa Inggris.
BERT memanfaatkan training bidirectional Transformer, dimana mereka tidak hanya membaca kata dari kiri ke kanan atau kanan ke kiri, namun melihat keseluruhan kalimat. Hal ini membuat BERT belajar tidak hanya dari 1 sisi, namun dari seluruh bagian yang ada di sekitarnya (kiri dan kanan). Hal ini dikembangkan karena arti sebuah kata dapat berubah saat kalimat semakin panjang.

## Algoritma Deep Learning menggunakan fastText
FastText adalah sebuah  open-source library yang dikembangkan oleh Facebook AI Research Lab. Fokus utama dari fastText adalah untuk memberikan solusi terukur untuk proses klasifikasi dan representasi teks dalam memproses dataset yang besar dengan cepat dan akurat. Fungsi yang digunakan fastText untuk melakukan komputasinya adalah: Hierarchical Softmax, Word n-grams
