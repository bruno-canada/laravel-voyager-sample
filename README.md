<h3 align="center">PHP with Laravel & Voyager Frontend Framework</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> This is a simple example of a PHP web application start up structure using Laravel and Voyager framework.
    <br>
</p>

## 📝 Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Built Using](#built_using)

## 🧐 About <a name = "about"></a>

Write about 1-2 paragraphs describing the purpose of your project.

## 🏁 Getting Started <a name = "getting_started"></a>

### Prerequisites

```
LAMP stack
Laravel installed
```

### Installing

You need to have a LAMP stack environment up and running to install this application.

1) Install LAMP stack
2) Install Laravel
3) Download this package
4) Import the database backup provided from the folder "sql-dummy", from your MYSQL command line console type:
```
$mysql: create database laravel; 
$mysql: laravel < [Your Folder]laravel.sql
```

5) Paste the content of the folder "laravel-voyager-setup" inside your public folder of your LAMP (E.g. public_html or www/html);

6) From inside your public folder type the following command:
```
php artisan serve
```

Done. Now you can access: http://localhost:port/

To access Voyager try: http://localhost:port/admin
User: admin@admin.com
Password: password

## ⛏️ Built Using <a name = "built_using"></a>

- [PHP](https://www.php.net/) - Programming language
- [Laravel](https://laravel.com/) - PHP Framework
- [Voyager](https://voyager.devdojo.com/) - Laravel Admin Package
- [MYSQL](https://www.mysql.com/) - RDBMS (Relational Database Management System)

