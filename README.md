<h1 align="center">Selamat datang di Aplikasi Perpustakaan👋</h1>

[](url)
![Screenshot_2021-01-30 Figma(1)](https://user-images.githubusercontent.com/55536560/106356894-60009700-6335-11eb-97c9-185bca17066c.png)

[![](https://img.shields.io/github/issues/rizalihwan/perpustakaan?style=flat-square)](https://img.shields.io/github/issues/rizalihwan/perpustakaan?style=flat-square) ![](https://img.shields.io/github/stars/rizalihwan/perpustakaan?style=flat-square)
![](https://img.shields.io/github/forks/rizalihwan/perpustakaan?style=flat-square) ![](https://img.shields.io/github/license/rizalihwan/perpustakaan?style=flat-square) [![saythanks](https://img.shields.io/badge/say-thanks-ff69b4.svg?style=flat-square)](https://saythanks.io/to/zaidanline67%40gmail.com) [![HitCount](http://hits.dwyl.com/zuramai/https://github.com/zuramai/kelaskita.svg)](http://hits.dwyl.com/zuramai/https://github.com/zuramai/kelaskita)  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=flat-square)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) [![made-for-VSCode](https://img.shields.io/badge/Made%20for-VSCode-1f425f.svg?style=flat-square)](https://code.visualstudio.com/) [![GitHub followers](https://img.shields.io/github/followers/zuramai.svg?style=flat-square&label=Follow&maxAge=2592000)](https://github.com/zuramai?tab=followers)

### 🤔 Apa itu Perpustakaan?
Web Perpustakaan Open Source yang dibuat oleh <a href="https://github.com/rizalihwan"> Rizal Ihwan Sulaiman. </a> **Perpustakaan adalah website peminjaman dan pengembalian buku di perpustakaan.** Perpustakaan dibuat untuk memudahkan proses peminjaman dan pengembalian buku dengan mudah.

### 🎉 Kenapa dibuat Open Source?
Untuk memudahkan peminjaman dan pengembalian buku di perpustakaan secara digital. Dan untuk bahan belajar bagi yang ingin mempelajari framework Laravel.

### 📆 <a href="#">Release Date</a>
- 31 January 2021

------------


## Installation
1. Open your terminal and go to your `~/htdocs` folder.
2. Clone this repository `git clone https://github.com/rizalihwan/perpustakaan.git`
3. Go inside to folder by `cd perpustakaan`
4. Run `composer install`
5. Create `.env` file with command `cp .env.example .env`
6. Generate key inside `.env` file by `php artisan key:generate`
7. Start your PGAdmin / Etc service
8. Create database on PGAdmin panel, example name: `db_laravel`
9. Open `.env` file and config your database:
    ```sh
    DB_DATABASE='db_laravel'
10. Then run the seeder `php artisan db:fresh` because this command for migrate tables & running seed.
10. Start your local server `php artisan serve`
11. Open link `localhost:8000` as default on your browser
12. Login with:
    |Level|Username|Password|
    |:----|:------:|-------:|
    |ADMIN|admin|password|
    |SISWA|siswa|password|

## Contributing

Thank you for considering contributing to my project! How to contribute:
1. Fork this Application
2. Create branch `git checkout -b yourName/develop`
3. Commit your contribution `git commit -m "New Feature has been Added"`
4. Push to your branch `git push origin yourName/develop`
5. Create Pull Request

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## Contact Info

Feel free to ask me at
- [Telegram](https://t.me/ihw_me/).

