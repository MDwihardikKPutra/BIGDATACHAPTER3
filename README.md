# BIGDATACHAPTER3
## Nama      : M Dwihardik K Putra
## Kelas     : TI - 3C
## No. Absen : 11

## Hasil

## Accumulator


![1](https://user-images.githubusercontent.com/90185910/227858106-853294f1-5897-4aa4-b0ad-1f2f2345f90c.png)
## Keterangan : kode tersebut adalah kode tersebut digunakan untuk menghitung jumlah dari semua elemen dalam RDD menggunakan accumulator pada Apache Spark.

## Broadcast

![2  BROADCAST](https://user-images.githubusercontent.com/90185910/227858140-c59b9a9e-d0ac-400f-81cc-33ee661804fe.png)
## Keterangan : Kode tersebut digunakan untuk membuat sebuah variabel yang disiarkan ke seluruh node pada cluster Spark dengan menggunakan fungsi broadcast, kemudian mengembalikan nilai dari variabel tersebut dengan memanggil broadcastVar.value


## PairRDD

![3 PairRDD](https://user-images.githubusercontent.com/90185910/227858164-b62e7b94-d23a-473f-b2bb-ac93f70ae270.png)
## Keterangan : Kode tersebut digunakan untuk membuat RDD dengan nama myRDD yang berisi tiga string, kemudian mengubah RDD tersebut menjadi RDD pasangan menggunakan fungsi map. Selanjutnya, fungsi keys dan values digunakan untuk mengambil kunci dan nilai dari RDD pasangan tersebut, dan fungsi collect digunakan untuk mengembalikan daftar kunci dan nilai. Dengan demikian, kode tersebut menghasilkan daftar kunci dan nilai dari RDD pasangan secara terpisah.


## SystemCommandsOutput

![6  SystemCommandsOutput](https://user-images.githubusercontent.com/90185910/227858196-e38c8ae7-7d48-485b-83ad-63c4dc9da87b.png)
## Keterangan : 


## SystemCommandsReturnCode

![7  SystemCommandsReturn](https://user-images.githubusercontent.com/90185910/227858208-4cb2afc4-9b16-4120-a22d-93a7390a96db.png)


## UnderstandingRDDs
![4  UndersatndingRDD](https://user-images.githubusercontent.com/90185910/227858297-49d11020-dba3-42cd-bd87-06abf1c94dad.png)



## WordCount

![wordcount png](https://user-images.githubusercontent.com/90185910/227858617-8e5b03f5-b603-45c3-945f-03e4312c2888.jpg)

TUGAS

## Kode 1 terdiri dari beberapa komponen Spark yaitu SparkContext (sc), Accumulator, Parallelize, Lambda, dan Value.
\sc digunakan untuk membuat RDD dan memanggil fungsi-fungsi di Spark. 
\accumulator digunakan untuk mengakumulasi nilai dari seluruh task di RDD, 
\parallelize untuk membuat RDD dari koleksi di memori, 
\lambda untuk menentukan fungsi transformasi, dan value untuk menyimpan data yang akan diolah dalam RDD.

## 

