<p align="center">
  <a href="https://v5.getbootstrap.com/">
    <img src="https://imgur.com/download/B9OYwBu/" alt="Header" width="100%">
  </a>
</p>

<h3 align="center">Implementation Server Client PHP(MySQL) and Android </br> Case Stud: Login Service In PHP And MySQL For Android Applications</h3>

## Need

<i>GNU / Linux</i>
- [Apache](https://directory.apache.org/studio/download/download-linux.html) or [Nginx](http://nginx.org/en/linux_packages.html)
- [PHP](https://www.php.net/manual/en/install.unix.debian.php)
- [PHP-fpm](https://php-fpm.org/)
- [Mysql](https://dev.mysql.com/downloads/os-linux.html) or [Mariadb](https://downloads.mariadb.org/)

<i>Windows</i>
- [XAMPP](https://www.apachefriends.org/download.html) or [Laragon](https://laragon.org/download/index.html)

## Demo
[Visit](http://dhnnys.000webhostapp.com/P9/)

## Qna
1. why I can't connect to my localhost and database:
```
$conn = new mysqli('localhost', 'izu(change you user databases)', 'toor(change you password database)');
mysqli_select_db($conn, 'db_member');
```
2. why I can't connect to my table database:
```
$getData = "SELECT `ur_Id`,`ur_username`,`ur_password` FROM `tbl_user(this is table name you can change)` WHERE `ur_username`='" .$email."'
and `ur_password`='".$password."'";
```
## Thanks 💙
- [Nirav Daraniya](https://www.c-sharpcorner.com/article/login-service-in-php-and-mysql-for-android-application/)
