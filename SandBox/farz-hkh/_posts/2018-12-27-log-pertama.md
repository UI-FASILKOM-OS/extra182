Github adalah salah satu tempat untuk berkolabarasi menggabungkan beberapa kode dari sumber programmer yang berbeda-beda. Hal ini sangat dibutuhkan untuk para programmer yang ingin berkolaborasi dengan cara remote.
Github kali ini membutuhkan beberapa program dependency lain yaitu Git, Jekyll dan ruby. Pastikan kita sudah menginstall itu semua.

1.Pertama kita membutuhkan Github account.

![images](https://raw.githubusercontent.com/farz-hkh/extra182/master/assets/images/github_akun.png)

Kita dapat membuatnya dengan Sign Up atau Sign In(jika sudah ada)

2.Setelah kita membuat github account, kita dapat langsung membuat proyek awal. Katakanlah extra1xx dan dalam keadaan public. Akan lebih baik juga jika memilih README untuk menjelaskan Github Pages kita.

![images](https://raw.githubusercontent.com/farz-hkh/extra182/master/assets/images/github_repo.png)

3.Kemudian kita setting Github pages kita untuk melihat sumber personal kita contohnya kita memilih sumber dari master branch. Kita juga dapat memilih Theme untuk Github Pages kita dan kita juga dapat kebebasan untuk mengcustom domain url kita, tapi defaultnya tidak perlu(gunakan jika memang ingin).

![images](https://raw.githubusercontent.com/farz-hkh/extra182/master/assets/images/github_pages.png)

4.Setelah itu kita perlu mengclone git yang kita buat tersebut ke pc atau komputer kita(dapat juga clone git).

![images](https://raw.githubusercontent.com/farz-hkh/extra182/master/assets/images/github_clone.png)

5.Setelah itu kita buat folder yang bernama "_posts" yang berisi log pengerjaan kita, kemudian kita buat log txt yang berisi tutorial-tutorial seperti pada txt saat ini.

6.Kita buat tutorialnya mengenai apa saja yang dilakukan pada hari ini dan bagaimana step by step yang dikerjakan.

7.Setelah kita membuat itu semua, maka kita dapat menambahkan di repository kita yaitu extra1xx, dengan menggunakan cmd yaitu
```PS
"git add ."
```
kemudian buat pesan string untuk commit dengan contoh
```PS
"git commit -m "Percobaan"
```
setelah itu kita bisa mempush dengan cara
```PS
"git push -u origin master".
```

8.Akhirnya kita dapat melihat folder kita yang bernama "_posts" yang berada di repository "extra1xx".
