# Listview dengan Provider

Challenge untuk UTS :

1. Tambahkan fitur untuk validasi input di tambah task.
- Menambahkan Validation model
- Menambahkan validation function di tasklist 
- Menambahkan cek error di taskname pada addtask
- Menghapus const pada main di route karena error<br>
Contoh Gambar : <br>
![2](https://user-images.githubusercontent.com/85380380/199454813-e053fccc-c32e-4b2b-827b-caffd5323fd8.PNG)
![14](https://user-images.githubusercontent.com/85380380/199454906-ad54f6a1-f2e6-44ed-a102-d41731fb692d.PNG)


2. Tambahkan fitur untuk disable button tambah task jika validasi input masih error.
- Menambahkan context dan pengencekan validation pada function onpressed di addtask<br>
Contoh Gambar : <br>
![14](https://user-images.githubusercontent.com/85380380/199454958-ac384902-9d59-4755-a264-d0f4a56fa9f9.PNG)



3. Tambahkan fitur swipe left delete task
- Meggunakan onDismissed endToStart untuk dapat mengaktifkan swipe left
- Kemudian dipanggil function pada tasklist dan database_service untuk melakukan delete<br>
Contoh Gambar : <br>
![12](https://user-images.githubusercontent.com/85380380/199454974-37216bb9-d21c-4dfa-abd0-268f80b37b24.png)


4. Tambahkan fitur swipe right go to edit task page
- Menggunakan onDismissed startToEnd untuk dapat mengaktifkan swipe right
- Kemudian dipanggil route untuk dapat berpindah page<br>
Contoh Gambar : <br>
![13](https://user-images.githubusercontent.com/85380380/199454989-818b80f8-0685-4eec-b4f9-758299e53169.png)


5. Tambahkan fitur edit task.
- Membuat page baru dengan form disamakan addtask
- Merubah fungsi yang dapat memanggil data pada sqlite pada tasklist dan database_service
- Menambahkan route pada main untuk dapat berpindah page<br>
Contoh Gambar : <br>
![9](https://user-images.githubusercontent.com/85380380/199455832-c5bc1c30-a13e-415e-80ac-24bbb9f9da27.PNG)



6. Tambahkan fitur validasi input di edit task.
- Menambahkan Validation model
- Menambahkan validation function di tasklist 
- Menambahkan cek error di taskname pada editTask<br>
Contoh Gambar : <br>
![9](https://user-images.githubusercontent.com/85380380/199455032-88548154-fab5-438a-800d-a07bc13da4a4.PNG)
![8](https://user-images.githubusercontent.com/85380380/199455051-584b61f6-463c-4a93-b046-2d9c56511deb.PNG)


7. Tambahkan fitur disable button edit task jika validasi input masih error.
- Menambahkan context dan pengencekan validation pada function onpressed di addtask<br>
Contoh Gambar : <br>
![4](https://user-images.githubusercontent.com/85380380/199455075-371df5ab-ded3-47a7-8b9c-0d9af4f408cf.PNG)
