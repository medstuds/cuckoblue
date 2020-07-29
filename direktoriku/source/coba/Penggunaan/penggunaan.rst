Penggunaan
===========

Input Sample
^^^^^^^^^^^^^^^

Sebelum menerapkan Cuckoo Sandbox sebagai analisis malware, terlebih dahulu jalankan cuckoo seperti pada proses instalasi.


1. Akses web interface cuckoo di web browser dengan alamat IP 103.206.253.179:8080:

.. image:: 4.png 

2. Kemudian pengambilan data pada Dionaea atau sample data yang akan dianalisis, pada percobaan ini dilakukan pengambilan data dengan sumber data pada kelompok1 dengan menggunakan perintah scp untuk menyalin file dan meletakkan pada direktori yang sesuai:

..  image:: 5.png

3. Pengambilan dilakukan juga data pada Cowrie. Kemudian, masukkan file yang sudah didapatkan ke dalam cuckoo:

..  image:: 6.png


Analisis Sample
^^^^^^^^^^^^^^^^

1. Pada gambar dibawah ini menunjukkan jika berhasil melakukan input sample untuk dianalisis pada cuckoo:

..  image:: 7.png

2. Melakukan proses analisis, jika akan melakukan analisis akan masuk pada daftar Tasks dengan pemberian ID sebagai inisial dengan keterangan detail lainnya, seperti pada gambar:

.. image:: 8.png

3. Melihat daftar file sebagai hasil analisis yang sudah diinputkan akan ditampilkan pada tampilan display Recent pada cuckoo:

..  image:: 9.png


4. Hal yang lebih menarik adalah pada cuckoo diberikan hasil dengan mengetahui detail file pada bagian Summary yang memuat informasi terkait file, pada bagian kiri cuckoo akan menyajikan fitur analisis terhadap file:

..  image:: 10.png

Tampilan bagian kiri cuckoo (fitur analisis detail terhadap file):

.. image:: 18.png


5. Kemudian dapat dilakukan Static Analysis:

..  image:: 11.png

tampilan lain pada Static Analysis:

..  image:: 12.png

6. Melihat file sample yang input dengan menggunakan Behavioral Analysis:

..  image:: 13.png

7. Dropped Files:

.. image:: 14.png

Dropped Buffers:

.. image:: 15.png

8. Process Memory:

..  image:: 16.png

9. Melakukan perbandingan dengan fitur Compare:

..  image:: 17.png

