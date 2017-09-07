
Search
##########

:Last Update: 6 September 2017
:Rev: 1.0

Description
***************
Modul search digunakan untuk melakukan pencarian data.

Requirements
******************
* modul list view

Rules
**************
1. Pencarian berdasarkan data yang terdapat dalam list view dan data detail list view yang terkait
2. Pencarian tidak berlaku untuk option, thumbnail, image
3. Apabila hasil pencarian tidak ditemukan maka keluar pesan untuk mengarahkan user menggunakan search option
4. Pencarian bisa dilakukan dengan huruf besar atau kecil (not case sensitif)

..note:: List pada search option akan ditentukan berdasarkan analisa

User Interface
****************
search default
===================
.. image:: /searchdefault.png

keterangan
----------



search option
===================
.. image:: /searchdefault.png


Back End
*************

Rules
===========
1. Metode pencarian untuk field text menggunakan %like% (mengandung kata tsb) 
2. Untuk inputan tanggal menggunakan format tanggal
3. Untuk inputan nilai menggunakan operator
4. Pada pencarian lebih dari satu search option menggunakan operator AND
5. Jika pencarian lebih dari satu search option yang sama menggunakan operator OR

