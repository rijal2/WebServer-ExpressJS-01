# WebServer-ExpressJS-01
MENGGUNAKAN VIEW ENGINE EXPRESSJS

01. Buka dokumentasi expressjs di expressjs.com
02. Kemudian ikuti panduan install express di VSC

    a. Lakukan "npm init" diterminal. Perintah ini akan menghasilkan file "package.json"
    b. Tulis pada terminal ==> $ npm install express --save
        pada akhir perintah tersebut terdapat "--save". Maksudnya agar express yang diinstall tersimpan ke dalam dependensi. Meskipun sebenarnya, dg menggunakan nodeJs yang ada, tanpa menuliskan "--save" pun akan tersimpan di despendensi.
        Bukti jika express sudah terinstall adalah munculnya folder node_modules dan file "package-lock.json"
    c. Jika menggunakan git hub, maka Buat File .gitignore.
        File ini berfungsi untuk melindungi file atau folder agar tidak ter-record oleh git. Caranya adalah dengan menuliskan nama folder atau file yang kita pilih agar tidak ter-record oleh git.

03. Gunakan ExpressJS, caranya:

    a. Ambil template starter nya di https://expressjs.com/en/starter/hello-world.html
    b. Salin ke app.js

04. Install Nodemoon agar ketika terjadi perubahan sistem sudah otomatis me-refresh
05. Setelah diinstall, Tambahkan "start": "nodemon app.js" pada object scripts yang ada di dalam file package.json.
06. Jalankan nodemon pada terminal dengan perintah "npm run start"
