# Capstone_2
##Capstone 2 Data Analysis Online Retail Shipping

# <font color ='yellow'>Latar Belakang</font>
- Sebuah perusahaan memiliki bidang usaha retail yang menjual barangnya secara online.
- perusahaan memiliki sebuah gudang yang dibagi ke dalam 5 blok (blok A hingga E). 
- Untuk mengirimkan barang dari gudang ke pelanggan, terdapat 3 mode transportasi yang digunakan yaitu kapal, pesawat dan jalan raya (Ship, Flight and Road). 
- Perusahaan memiliki customer care yang ditugaskan untuk menangani pertanyaan pelanggan terkait pengiriman barang. 
- Pelanggan dapat memberikan rating dari angka 1 hingga 5 atas pengiriman yang telah dilakukan. 
- Perusahaan menyerahkan data atas pengirimannya kepada seorang data analyst untuk dianalisa lebih lanjut terkait kinerja pengiriman yang telah dilakukannya selama ini.

# Proses Bisnis
![alt text](https://github.com/ariefkurniawan95/Capstone_2/blob/main/shipping.JPG?raw=true)

# Warehouse Layout
![alt text](https://github.com/ariefkurniawan95/Capstone_2/blob/main/warehouse_blocks.JPG?raw=true)

# <font color ='white'> Kamus data </font>
#### Terdapat 12 kolom yang terdapat pada dataset Online Retail Shipping, yakni :
- Cost_of_the_Product   : harga pokok product dalam satuan US dollar.
- Customer_care_calls   : jumlah telepon yang terjadi untuk pengiriman terkait
- Customer_rating       : penilaian konsumen atas pengiriman (1 paling kecil dan 5 paling besar)
- Discount_offered      : diskon yang ditawarkan 
- Gender                : Pria dan Wanita (Male dan Female)
- ID                    : nomor id pelanggan
- Mode_of_Shipment      : mode pengiriman barang (kapal, pesawat dan jalan)
- Prior_purchases       : jumlah pembelian sebelumnya.
- Product Importance    : perusahaan mengkategorikan produk kedalam beberapa parameter (low, medium, high)
- Warehouse_block       : blok gudang asal barang berasal
- Weight_in_gms         : berat dalam satuan gram


# <font color ='yellow'>Conclusion : </font>
- Tidak terdapat perbedaan dari segi jumlah pengiriman kepada konsumen baik pria ataupun wanita.
- Tidak terdapat perbedaan harga barang antara pelanggan pria dengan pelanggan wanita.
- Konsumen wanita tidak lebih banyak menelpon customer_care daripada konsumen pria.
- Warehouse area E mengirim lebih banyak barang dibandingkan dengan warehouse lainnya.
- Perusahaan tidak memiliki strategi untuk menempatkan barang berdasarkan berat untuk memudahkan keluar masuknya barang di warehouse.
- Perusahaan menggunakan mode pengiriman yang paling banyak digunakan adalah Kapal (Ship). 
- Tidak terdapat perbedaan mode pengiriman berdasarkan berat barang. 
- Product_importance 'high' justru yang paling banyak keterlambatan pengirimannya. 
- Semakin sering konsumen menghubungi customer care, maka semakin kecil tingkat keterlambatannya.
- Kinerja pengiriman (keterlambatan) tidak mempengaruhi nilai rating.
- Perusahaan tidak memiliki strategi untuk memberikan diskon terhadap konsumen yang loyal (prior purchasesnya banyak).
- Barang dengan product_importancenya 'high' memiliki diskon yang lebih besar dibandingkan dengan kategori low dan medium.
- Perusahaan tidak memiliki strategi khusus dalam memberikan diskon untuk pelanggan dengan prior_purchasesnya tinggi. 

# <font color ='yellow'>Recommendation :</font>
- Perusahaan harus memiliki strategi untuk menempatkan barang berdasarkan berat untuk kemudahan keluar masuknya barang supaya lebih cepat (re-layout warehouse). 
- Seharusnya perusahaan memprioritaskan barang dengan product_importance high untuk dikirim lebih cepat supaya tidak terlambat sampai di konsumen.
- Seharusnya perusahaan dapat melakukan pengaturan ulang perihal product importance dengan mode pengiriman. 
    - Untuk barang dengan kategori product_importance high dikirim menggunakan pesawat (flight)
    - Untuk barang dengan kategori product_importance medium dikirim menggunakan truk (road)
    - Untuk barang dengan kategori product_importance low dikirim menggunakan kapal (ship)
- Perusahaan harus memfokuskan pada penurunan tingkat keterlambatan barang. 
- Seharusnya perusahaan memiliki promo / diskon khusus untuk pelanggan yang loyal (prior_purchases-nya tinggi)


