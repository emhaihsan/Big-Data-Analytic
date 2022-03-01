# Repository Tugas Kuliah Analisis Big Data

### mtsamples.csv
Data transkrip medis yang diambil dari [mtsamples](https://www.mtsamples.com). Data terdiri 5003 record dan 5 kolom yaitu:
* Type/Specialty: Tipe Penyakit / Bidang
* Sample Name	: Nama Sampel
* Description : Deskripsi singkat terkait sampel transkrip	
* Transcript : Detail transkrip
* Keywords : Kata kunci terkait

### mtsamples_scraping.ipynb
Notebook untuk melakukan scraping pada web [mtsamples](https://www.mtsamples.com). 
Scraping menggunakan bahasa pemrograman Python dan library [Beautiful Soup](https://beautiful-soup-4.readthedocs.io/en/latest/#) 

### mapper.py & reducer.py
Script Python untuk melakukan proses mapReduce pada text.
