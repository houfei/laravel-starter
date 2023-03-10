# Laravel Starter

![PhpStorm](https://img.shields.io/badge/phpstorm-143?style=for-the-badge&logo=phpstorm&logoColor=black&color=black&labelColor=darkorchid)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white)
![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

## 开发和生产环境配置信息

- 生产环境：[https://your-domain.com/](https://your-domain.com/)
- 本地环境：[https://laravel.test/](https://laravel.test/)

### 创建指定字符集数据库

```mysql
CREATE DATABASE `laravel` DEFAULT CHARACTER SET `utf8mb4` COLLATE `utf8mb4_general_ci`;
```

### Serving Sites with Laravel Valet

本地需已配置 [Laravel Valet](https://laravel.com/docs/10.x/valet) 环境

- 使用 `http://laravel.test` 访问：`valet link laravel`
- 使用 `https://laravel.test` 访问：`valet secure laravel`

***

## 扩展安装和使用信息

### 运行 Laravel Pint 扩展

文档: [Laravel Pint](https://laravel.com/docs/10.x/pint)

```bash
# 对项目目录执行格式化
./vendor/bin/pint
# 在指定目录中执行格式化
./vendor/bin/pint app/Models
# 对指定文件执行格式化
./vendor/bin/pint app/Models/User.php
```

### 运行 Laravel Breeze 扩展

文档: [Laravel Breeze](https://laravel.com/docs/10.x/starter-kits#laravel-breeze)

```bash
composer require laravel/breeze --dev
php artisan breeze:install {--blade --dark --pest}
php artisan migrate
npm install && npm run dev
```
