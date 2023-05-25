# <p align="center"><b>URASCRIPT - Laravel and MySQL</b></p>

<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

Graphical application for modeling scripts for interpretation by the URA

**The code for this project is private**

## Prerequisites

This tutorial assumes you have PHP and MySQL installed on your system. Follow the instructions for your operating system to install both of them.

You also need to be familiar with Linux/macOS bash where we'll be executing the commands in this tutorial.

Familiarly with PHP is required since Laravel is based on PHP.

For development I will be using a Ubuntu 20.04 machine so the commands in this tutorial are targeting this system but you should be able to follow this tutorial in any operating system you use.

# Laravel - URASCRIPT

Graphical application for modeling scripts for interpretation by the URA.

## Installation

Clone the repository-
```
git clone ...
```

Then cd into the folder with this command-
``` 
cd urascript
```

Then do a composer install
```
composer install
```

Then create a environment file using this command-
```
cp .env.example .env
```

Then edit `.env` file with appropriate credential for your database server. Just edit these two parameter(`DB_USERNAME`, `DB_PASSWORD`).

Then create a database named `urascript` and then do a database migration using this command
```
php artisan migrate --seed
```

## Run server

Run server using this command-
```
php artisan serve
```

Then go to `http://localhost:8000` from your browser and see the app.

## Screenshot

![](https://thumbs2.imgbox.com/dd/fc/VJJgI9RD_t.png)
![](https://thumbs2.imgbox.com/85/80/AF2BE7rF_t.png)
![](https://thumbs2.imgbox.com/cf/58/IqqWIsTZ_t.png)

## Credits

- [MEZ](https://github.com/marcioezani)
