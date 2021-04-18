# FuzzyLogicMamdani
Fuzzy logic yang digunakan yaitu model fuzzy logic mamdani, dimana program ini berjalan menggunakan IPython / Jupyter Notebook. 

Libarary yang digunakan :
1. Numpy
2. Scikit-Fuzzy
3. Matplotlib

Terdapat 2 input, yaitu 
1. Project Funding dengan fuzzyset yaitu : trapesium, segitiga, dan trapesium. Dengan variable semesta pembicaraannya 0 - 100 untuk resikonya juga memiliki fuzzyset funding yaitu Inadequate, Marginal dan Adequate.
2. Project Staffing dengan fuzzyset yaitu : trapesium dan trapesium. Dengan variabel semesta pembicaraannya 0 - 100 untuk resikonya juga memiliki fuzzyset staffing yaitu small dan large.

Dan juga terdapat Project Risk dengan fuzzyset yaitu : trapesium, segitiga, dan trapesium. Dengan variable semesta pembicaraanya 0 - 100 untuk resikonya juga memiliki fuzzyset risk yaitu low, medium dan high.

Dengan permasalahan bahwa project fundingnya 26% dan project staffingnya 57.5%. 
Kemudian rulesnya yaitu 
1. Project Funding output derajat keanggotaanya nya, inadequate = 0.5, marginal = 0.2 dan adequate = 0.0.
2. Project Staffing outputnya derajat keanggotaanya, small = 0,1 dan large = 0.7.

Dengan korelasi aturan dan output seperti berikut : 
Gambar 2
low = 0.1, normal = 0,2 dan high = 0,5.

Kesimpulan
Teknik yang digunakan pada model fuzzy mamdani adaah centroid technique. Yaitu metode ini mencari centre of gravity. Berikut hasilnya:
