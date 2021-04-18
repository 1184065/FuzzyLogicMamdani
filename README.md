# FuzzyLogicMamdani
Fuzzy logic yang digunakan yaitu model fuzzy logic mamdani, dimana program ini berjalan menggunakan IPython / Jupyter Notebook. 

Library yang digunakan :
1. Numpy
2. Scikit-Fuzzy
3. Matplotlib

Terdapat 2 input, yaitu :

1. Project Funding dengan fuzzyset yaitu : trapesium, segitiga, dan trapesium. Dengan variable semesta pembicaraannya 0 - 100 untuk resikonya juga memiliki fuzzyset funding yaitu Inadequate, Marginal dan Adequate.

![pfun](https://user-images.githubusercontent.com/44889084/115139924-dff9eb80-a05e-11eb-8c66-daa228fa124d.PNG)

2. Project Staffing dengan fuzzyset yaitu : trapesium dan trapesium. Dengan variabel semesta pembicaraannya 0 - 100 untuk resikonya juga memiliki fuzzyset staffing yaitu small dan large.

![pstuff](https://user-images.githubusercontent.com/44889084/115139934-eb4d1700-a05e-11eb-813a-22f9825e2ce2.PNG)

Dan juga terdapat Project Risk dengan fuzzyset yaitu : trapesium, segitiga, dan trapesium. Dengan variable semesta pembicaraanya 0 - 100 untuk resikonya juga memiliki fuzzyset risk yaitu low, medium dan high.

![prisk](https://user-images.githubusercontent.com/44889084/115139929-e720f980-a05e-11eb-8599-db3854d6f7be.PNG)

Dengan permasalahan bahwa project fundingnya 26% dan project staffingnya 57.5%. 
Kemudian rulesnya yaitu 
1. Project Funding output derajat keanggotaanyanya, inadequate = 0.5, marginal = 0.2 dan adequate = 0.0.
2. Project Staffing outputnya derajat keanggotaanya, small = 0,1 dan large = 0.7.

Dengan korelasi aturan dan output seperti berikut : 

![2](https://user-images.githubusercontent.com/44889084/115140123-edfc3c00-a05f-11eb-8b72-0e7b6e799815.PNG)

low = 0.1, normal = 0,2 dan high = 0,5.

Kesimpulan
Teknik yang digunakan pada model fuzzy mamdani ada;ah centroid technique. Yaitu metode ini mencari centre of gravity. 
Berikut hasilnya:
COG = (0+10+20)x0.1+(30+40+50+60)x0.2+(70+80+90+100)x0.5 / 0.1+0.1+0.1+0.2+0.2+0.2+0.2+0.5+0.5+0.5+0.5 = 67,4.
Centre of gravity digunakan untuk mencari titik yang membagi menjadi 2 bagian yang sama.
Namun jika menggunakan MOM (Min of Max) yaitu resiko dengan 80%.

![3](https://user-images.githubusercontent.com/44889084/115139939-f0aa6180-a05e-11eb-91f7-67b86d524c34.PNG)

