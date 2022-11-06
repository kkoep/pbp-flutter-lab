# Pertanyaan Tugas 7

## Referensi
1. [Tambah lebih banyak button](https://www.fluttercampus.com/guide/19/how-to-add-multiple-floating-action-buttons-in-one-screen-flutter-app/)
2. [Referensi alignment button](https://stackoverflow.com/questions/72152176/how-to-put-buttons-on-two-ends-of-screen-in-flutter)
3. [Referensi change color # 1](https://programmingwithswift.com/change-button-color-on-press-with-flutter/)
4. [Referensi change color # 2](https://www.flutterbeads.com/change-text-color-in-flutter/#:~:text=its%20color%20parameter.-,Steps,the%20color%20of%20your%20choice.)
5. [If else](https://www.tutorialspoint.com/dart_programming/dart_programming_if_else_statement.htm)
6. [Hide button](https://stackoverflow.com/questions/44489804/how-to-show-hide-widgets-programmatically-in-flutter)

## Jawaban
1. Stateless widget adalah widget yang statis dan hanya akan mengikuti state awal yang telah diassign kepadanya dan tidak akan berubah meskipun data disekitarnya berubah. Namun, stateful widget adalah widget yang lebih dinamis dan dapat berubah sesuai dengan data disekitarnya. Contoh dari stateless widget adalah increment button karena ia tidak akan berubah berapapun nilai counternya sedangkan untuk stateful widget contohnya adalah counter serta text karena ia akan berubah setiap button diclick.
2. Dalam proyek ini saya menggunakan dua widget yaitu Text dan Floating Action Button. Text ini memiliki fungsi untuk menampilkan text yang ingin ditampilkan dalam program sementara Floating Action Button berfungsi untuk membuat sebuah button yang dapat kita gunakan untuk melaksanakan sebuah action atau fungsi yang telah diassign kepadanya.
3. `setState()` berfungsi untuk memanggil kembali build method yang telah kita definisikan agar ia merepresentasikan value baru yang telah kita update. Variabel yang akan dipengaruhi oleh `setState()` sendiri adalah semua variabel yang masuk didalam lingkupnya. 
4. `const` mengassign value disaat compile time sehingga pada dasarnya value yang diassign bersifat immutable dan sudah tidak dapat diganti lagi tapi ini juga berarti bahwa hanya value yang dapat diassign saat compile time yang dapat diberikan `const`. Namun, untuk `final` ia bersifat mirip dengan `val` pada kotlin yakni ia bersifat immutable kecuali apabila yang diberikan adalah sebuah collection data yang masih bersifat mutable seperti list tapi untuk string maupun tipe data lainnya yang diberikan `final` akan bersifat immutable dan hanya akan mengikuti value awal yang telah diassign kepadanya. 
5. Untuk implementasi tugas diatas saya menerapkannya dengan beberapa referensi. Pertama-tama saya menambahkan lagi button untuk mengurangi counter serta mengalignnya menggunakan referensi satu dan dua. Selanjutnya saya membuat function set text untuk mengatur text berdasarkan posisi counter saat ini menggunakan referensi 3 dan 4. Dalam penerapan hal-hal tersebut saya menggunakan conditional statement begitu pula untuk bonus berdasarkan referensi ke 5 dan 6.