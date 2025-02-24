<p align="center">
  <img src="https://github.com/Raafina/Sitoya/blob/main/public/assets/img/sitoyaLogo.png" alt="CMS Lokapath Dashboard" width="30%">
</p>

## Sitoya
Sitoya is an website designed to help the management of Artesian Water in Desa Salam Serep , Kota Semarang in recording payments from customers and managing cash flow efficiently. The application provides comprehensive financial reports, enabling administrators to monitor finances and operations.

## 🚀 Key Feature
<ul>
    <li>Payment Recording: Easily track and manage customer transactions.</li>
    <li>Cash Flow Management: Monitor income and expenses.</li>
    <li>Financial Reports: Generate detailed reports for financial analysis and evaluation.</li>
</ul>

## 🛠️ Tech Stack
<ol>
    <li>Laravel</li>
    <li>Bootstrap</li>
    <li>MySQL/SQLite</li>
</ol>

## 🎯How To Use
<ol>
    <li>
        <p>Clone this repository</p>
        <p><pre>git clone https://github.com/Raafina/CMS-Lokapath.git</pre></p>
    </li>
    <li>
        <p>Navigate to the project directory</p>
        <p><pre>cd Sitoya</pre></p>
    </li>
    <li>
        <p>Install dependencies</p>
        <p><pre>composer install</pre></p>
    </li>
    <li>
        <p>Configure the .env file/SQLite</p>
        <ul>
            <li>Duplicate .env.example and rename it to .env</li>
            <li>Adjust the database and environment configurations</li>
        </ul>
        <p><pre>php artisan key:generate</pre></p>
    </li>
    <li>
        <p>Run database migrations</p>
        <p><pre>php artisan migrate --seed</pre></p>
    </li>
    <li>
        <p>Start the application</p>
        <p><pre>php artisan serve</pre></p>
    </li>
</ol>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>
