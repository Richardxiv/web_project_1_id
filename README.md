# web_project_1_id

Indonesian web project 1

## deskripsi dari projek

projek ini dibuat menggunakan html dan css.
tujuan dari projek ini, agar saya dapat lebih terbiasa dan mendalami html dan css dengan sangat baik

### teknik yang digunakan dalam projek ini

cara saya membuat transisi pada setip link di project ini

1. berikan style
   transition: opacity 1s linear ;
2. buat block baru dengan nama yang sama tetapi tambahkan pseudo class :hover
3. di block tersebut tambahkan
   opacity: 0.5;

cara menambahkan animasi pada square dan triangle

1. tambahkan @keyframes di awal projek dengan nama rotation
   @keyframes rotation {
   from {
   transform: rotate(0deg);
   }
   to {
   transform: rotate(360deg);
   }
   }

2. tambhakan style animation dengan nama rotation dan attribute lainnya
   transform: rotate(-15deg);
   animation: rotation 20s linear infinite;

cara menamkbahakan video pada projek ini

1. pergi ke video yang diiginkan di youtube dan pilih embed code
2. copy dan paste code ke blok video dan atur width dan height di style iframe
3. supaya meletakan video di atas block oakley kita harus mengatur margin-bottom:-75px;

membuat gambar menjadi link dan bertransisi

1. buat tag <table> dan buat tag <a> dengan kelas yang sesuai dan berikan tag <img> didalamnya.
   <table class="logo__zone">
   <tr>
   <td><a href="#"><img class="resources**logo"src="./logo/resources-tedED.png" alt="tedED.png"></a></td>
   <td><a href="#"><img class="resources**logo" src="./logo/resources-Medium.png" alt="Medium.png"></a></td></td>
   <td><a href="#"><img class="resources__logo" src="./logo/resources-dezeen.png" alt="dezeen.png"></a></td></td>
   <td><a href="#"><img class="resources__logo" src="./logo/resources-goodreads.png" alt="goodreads.png"></a></td></td>
   </tr>
   </table>
2. kemudian berikan transisi dengan cara yang sama seperti diatas
