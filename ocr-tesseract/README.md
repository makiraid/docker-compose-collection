# OCR API Build With Python Tesseract

## Resources
[Github Repository](https://github.com/M1n007/ocr-simple-api) \
[Docker Hub](https://hub.docker.com/repository/docker/kirahxr/ocr-python) \
[Postman Collection](https://www.getpostman.com/collections/62b8b6aa4c324c27d6d3)

## Modules!

  - flask
  - opencv-contrib-python-headless
  - pytesseract
  - gevent
  - pillow
  - spacy
  - numpy (no required)

## Features!

  - Find word at Images

## Result

#### Sample Json Result

```json
{
    "data": {
        "imageResult": "iVBORw0KGgoAAAANSUhEUgAABGoAAATACAIAAAAnUjbZAAAgAElxxxxxx==",
        "text": "BAB1\nKorupsi dan Perburuan Rente\nPENDAHULUAN\n\nMasalah korupsi di negera Indonesia benar-benar harus menjadi atensi semua elemen bangsa.\nSulit sekali membersihkan korupsi di negeri ini. Kotoran tersebar di mana-mana. Keelokan\nnegeri untaian zamrud khatulistiwa kian memudar. Bersih-bersih menjadi percuma karena\nkembali terlumuri sampah. Awal tahun 2020 yang sejatinya disambut dengan harapan baru,\njustru dikagetkan dengan operasi tangkap tangan.\n\nInsiden penangkapan pejabat publik melalui operasi tangkap tangan (OTT) dalam waktu yang\nhampir bersamaan bisa jadi laksana fenomena gunung es. Itu berarti kasus serupa sejatinya\nbanyak, hanya belum terendus Komisi Pemberantasan Korupsi (KPK). Apalagi, pada tahun 2020\nsemua elite dan partai politik sedang bersiap menyongsong pemilihan kepala dacrah (Pilkada)\nserentak. Momentum tersebut potensial dimanfaatkan untuk memobilisasi sumber dana dari\nmana pun demi kepentingan pemenangan Pilkada.\n\nSejarah menunjukkan, perguruan tinggi selalu menjadi simbol perlawanan, tanpa terkecuali\nterhadap kejahatan korupsi, meskipun perguruan tinggi pun tak luput dari jerat kejahatan korupsi\ndan rent seeking activity. Perguruan tinggi yang di dalamnya ada mahasiswa dan dosen\nmerupakan perwujudan masyarakat sipil (civil society) yang dapat menjadi lokomotif dan\npelopor pemberantasan korupsi di negara ini. Sebagai perwujudan masyarakat sipil perguruan\ntinggi dapat menjadi gerakan penyeimbang dan kontrol terhadap lembaga penegak hukum dan\naparat keamanan yang berwenang memberantas korupsi.\n\nSalah satu upaya pemberantasan korupsi yang bisa dilakukan civitas akademika adalah melalui\nriset ekonomi politik tentang korupsi dan rent seeking activity.\n\nKorupsi berasal dari kata cerruptio atau corruptus, secara harafiah bermakna perilaku\nberbohong, tidak jujur, tidak bermoral, dapat disuap, mencuri dan lain sebagainya. Menurut\nKamus Umum Bahasa Indonesia, korupsi bermakna perbuatan busuk seperti penggelapan uang,\ndapat disuap. Korupsi berbagai macam jenisnya mengikuti perekmbangan teknologi.\n\nBaharudin lopa membagi korupsi menjadi dua bentuk, yaitu material/economic corruption dan\npolitical corruption, Bentuk pertama adalah yang lebih banyak menyangkut penyelewengan di\n\n1"
    },
    "err": false,
    "message": "successfully recognized image"
}

```

#### Sample Image Result

![Imgur Image](https://i.imgur.com/OWuoF6v.png)
