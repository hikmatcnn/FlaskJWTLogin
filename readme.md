**senin 07/02/2022:**

- [x] Membuat API Register dan Login
- [x] Belajar JWT token
- [x] testing pada Postman

1. /signup
   route ini menggunakan metode _POST_ dan berfungsi untuk register user ke database, menggunakan _form-data yg berisi 'name', 'email', 'password'_
   jika sukses maka outputnya data user (sesuai form yg diisikan)

2. /login'
   route ini menggunakan metode _POST_ dan berfungsi untuk login user ke sistem, menggunakan _form-data yg berisi 'email', 'password'_
   jika sukses maka outputnya token

3. /user
   route ini menggunakan metode _GET_ dan berfungsi untuk login user ke sistem, memerlukan data _Headers x-access-token : token yg didapatkan ketika login_
   jika sukses maka outputnya data user
