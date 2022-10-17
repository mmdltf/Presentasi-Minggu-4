

# **Presentasi-minggu-4**

## **Asynchronous Fetch dan Async-Await** 
Fetch merupakan sebuah fitur yang ada pada javascript untuk memudah kan kita mengakses database eksternal (API) atau bisa dibilang sebuah cara  dalam melakukan network request. Pada dasarnya fetch memanfaatkan sebuah **Promise** seperti yang sudah saya bahas sebelum nya. Namun, terdapat metode lain yaitu **Async-Await**. 
Penggunaan **Async-Await** tidak jauh berbeda dengan **Promise**, letak perbedaannya yaitu response handling nya. Ketika menggunakan **Promise** maka response handling yang digunakan adalah:

 1. **Then**
 2. **Catch**

Ketika kita meggunakan **Async-Await** maka response handling yang digunakan adalah :
 1. **Try**
 2. **Catch**
 
kemudian `await` didalam sebuah fungsi async merupakan sebuah expression  dimana ketika fungsi tereksekusi akan mem-pause ketika promise tersebut fiterima (fullfilled) atau ditolak (rejected) serta melanjutkan proses eksekusi sampai value pada fungsi tersebut berhasil didapatkan.
![enter image description here](https://i.postimg.cc/fLV2Djhp/image.png)

## **Git Hub (Kolaborasi)** 
gitHub merupakan sebuah version control berbentuk cloud yang digunakan untuk memantau secara detail sebuah update/ pembaruan pada sebuah projek serta berkolaborasi. Berkolaborasi menggunakan gitHub dapat dilakukan dengan memanfaatkan fitur `organization`salah satu nya. Penggunaan fitur tersebut dapat dilakukan dengan tahapan berikut:
 1. **Create Organization**
 Dalam tahapan ini leader pertama-tama harus men-create sebuah organization untuk wadah kolaborasi sebuah tim
 2. **Create Repository**
 Dilanjutkan dengan tahapan men-create sebuah repository yang bersifat public kemudian create sebuah branch. Setelah itu gabungkan branch dev ke branch main dengan pull request
 
### **Branch**
Branch merupakan sebuah cabang dari repository yang berfungsi sebagai wadah dalam sebuah proses develop project agar tidak mengganggu branch master dimana isinya sudah siap di deploy. Terdapat beberapa perintah dalam berkolaborasi di gitHub antara lain:
 1. ### Merge

Merge merupakan sebuah perintah yang digunakan untuk menggabungkan branch yang memiliki parent.


2. ### Rebase

Rebase merupakan sebuah perintah sama hal nya seperti merge namun letak perbedaannya adalah penggunaan rebase ketika branch tersebut tidak memiliki parent.




3. ### Pull Request
Pull request merupakan sebuah perintah yang digunakan untuk menggabungkan kode pada sebuah project yang kita modifikasi dengan main repository/ branch master.



4. ### Clone

Clone merupakan sebuah perintah yang digunakan untuk meng-clone sebuah repo ke local kita.




5. ### Push

Push merupakan sebuah perintah yang digunakan untuk mengirimkan project yang dimodifikasi ke repository.



6. ### Pull

Pull merupakan sebuah perintah yang digunakan untuk memperbarui repository lokal ke commit terkini, atau bisa dibilang pull digunakan untuk mengambil dan menggabungkan perubahan jarak-jauh.

7. ### Checkout

Checkout adalah sebuah proses untuk berpindah dari branch satu ke branch lainnya. 

## **Responsive (Bootstrap)** 
Responsive Web Design  sebenarnya merupakan sebuah cara yang digunakan agar website yang kita buat/garap dapat digunakan pada jenis device yang berbeda-beda seperti hal nya desktop, tablet maupun smartphone. Digunakan dalam hal ini yang dimaksud adalah ukuran tampilan nya tidak bersifat fix. Secara manual untuk membuat sebuah website menjadi responsive dapat menggunakan Media Query, contoh :
`@media screen (max-width: 600px) {
    }`max width ini mempunyai maksud ukuran layar maksimal 600px ketika lebih terdapat beberapa styling yang akan berubah tergantung dari modifikasi yang kita lakukan, begitu juga pada `@media screen (min-width: 368 px) {
    }`.


    
    
    
 
-   #### Satuan Yang Digunakan
    **EM**: Sebuah satuan yang bersifat relatif terhadap parent element.

	**REM**:  Sebuah satuan yang bersifat relatif terhadap root element (HTML tag)

	**%**: Sebuah satuan yang bersifat relatif terhadap parent element

	**VW**: Sebuah satuan yang bersifat relatif terhadap  viewport’s width (lebar)

	**VH**: Sebuah satuan yang bersifat relatif terhadap  viewport’s height (tinggi)


        

## Bootstrap 5

Bootstrap 5 merupakan sebuah framework yang memudahkan seorang developer dalam melakukan styling suatu website, dibandingkan kita menggunakan vanilla CSS waktu yang butuhkan sangat berbeda jauh. Ketika kita ingin menggunakan bootstrap hal yang pertama dilakukan (terdapat cara lainnya namun ini paling mudah) yaitu menaruh kode CDN pada head seperti dibawah ini

        

        
        <link
          rel="stylesheet"
          href="https://stackpath.bootstrapcdn.com/bootstrap/5.0.0-alpha1/css/bootstrap.min.css"
          integrity="sha384-giJF6kkoqNQ00vy+HMDP7azOuL0xtbfIcaT9wjKHr8RbDVddVHyTfAAsrekwKmP1"
          crossorigin="anonymous"
        />
        
   Sistem grid yang ada pada bootstrap itu memiliki 6 breakpoint bawaan seperti dibawah ini 
   -   Extra small (xs)
-   Small (sm)
-   Medium (md)
-   Large (lg)
-   Extra large (xl)
-   Extra extra large (xxl)

 dengan ukuran tiap breakpoint sebagai berikut :
![enter image description here](https://i.postimg.cc/3xJdtmpv/image.png)
-   ### Layout Bootstrap 5
    -   #### Container
        
  
        
    -   #### Row
        

    -   #### Column
        



