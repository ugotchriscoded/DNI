# 🆔 Proyect - DNI 

## 🪪 Project description
<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

I created a console application that calculates the letter of the **DNI** *(National Identity Document)*.

### Algorythm
- The number must be **between 0 and 99999999**
- We take the complete number of up to **8 digits** of our ID, divide it by **23** and keep the remainder of said division **(modulo 23).**
- Depending on the result, **from 0 to 22**, it will correspond to one of the following letters: *T, R, W, A, G, M, Y, F, P, D, X, B, N, J, Z, S, Q, V, H, L, C, K, E* (these data must be in a **database table**).
- If the data entered is NOT a number, a **message** must be indicated that *"the data entered is incorrect"* and the user must be asked again.
- The process **must be repeated** until the user enters a **valid number**.
- Everything will be done by **json** *(Api)*.

## Requirements
Minimum **coverage 70%**.

## :eye_speech_bubble: Working app

(insert screenshoots)

## :file_folder: Jira Backlog
![JIRA screenshot](https://github.com/user-attachments/assets/4705c0d0-581a-486c-9d56-e1cc915e9854)


## :paperclip: Installation requirements
:black_circle: XAMPP

:black_circle: Composer

:black_circle: Node.js (Installing NPM)

:black_circle: Xdebug 

:black_circle: Postman

> [!NOTE] 
If you can't install XAPP, you can also use another local server that supports MySQL and PHP.

## :scroll: Installation

### Step 1: Creating database

Creating a database in **Admin** **SQL**.

<img width="176" alt="database" src="https://github.com/user-attachments/assets/c2ff0b28-6b13-446e-aabf-89149ec242cc" />


### Step 2: Cloning repository

```php
https://github.com/ugotchriscoded/DNI.git
 ```
### Step 3: Putting everything up to date

In the *.env* file **remove** the *#* in these lines, enter the **name** of your **database** and **replace** *Laravel* with *sql*.

<p align="center"><img width="287" alt="image" src="https://github.com/user-attachments/assets/bdfec806-cdcc-4a05-a6bf-43a59cc7658e"></p>

### Server

To **run the server** enter this command:

```php
npm run dev
```

<p align="center"><img width="317" alt="image" src="https://github.com/user-attachments/assets/ff2e3e05-881e-49e7-9b02-e80db682cd3e"></p>


> [!WARNING]
> **DON'T work** on that terminal again, but you should keep it working. **DON'T KILL IT.**

To see the **running serve** enter the command:

```php
php artisan serve
```

<img width="410" alt="running server" src="https://github.com/user-attachments/assets/4db3d32b-2716-46e8-9e41-c89f43bde526" />


> [!NOTE]
> If you press Control and click the link it should take you to the main offers.


## 📝 Documentation (Endpoints)
All the functionalities work with **just one endpoint** introducing the number you want to process.

### :heavy_check_mark: Correct
**Returns** your number plus the corresponding letter.

### :heavy_multiplication_x: NOT correct
Shows an **error message** warning you to introduce a valid number.

### Assign Letter (GET)

```php
http://127.0.0.1:8000/api/offers/id
```
> [!NOTE]
> Introduce the number where the **id** goes.


## :white_check_mark: Tests

> [!IMPORTANT]
>  Testing the project so we can check if it works correctly using this command:

```php
php artisan test
```

<img width="389" alt="php artisan test" src="https://github.com/user-attachments/assets/20a00f72-01f4-4048-8522-c72b542b2cb0" />


### Coverage

Use this command:

```php
php artisan test --coverage
```

<img width="482" alt="test coverage" src="https://github.com/user-attachments/assets/01a187e1-57b7-4ac9-809c-8553e33c887e" />



## Authors
Developed by **Valeria Dobado Gonzalez**:
- **Github**: *https://github.com/ugotchriscoded/ugotchriscoded*
- **Linkendin**: *https://www.linkedin.com/in/valeria-dobado-gonzález-262060328/*
  
## Languages
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='php' src='https://img.shields.io/badge/php-100000?style=for-the-badge&logo=php&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='css3' src='https://img.shields.io/badge/css3-100000?style=for-the-badge&logo=css3&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='json' src='https://img.shields.io/badge/JSON-100000?style=for-the-badge&logo=json&logoColor=white&labelColor=000000&color=000000'/></a>

## Tools
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='github' src='https://img.shields.io/badge/github-100000?style=for-the-badge&logo=github&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='Laravel' src='https://img.shields.io/badge/Laravel-100000?style=for-the-badge&logo=Laravel&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='Git' src='https://img.shields.io/badge/git-100000?style=for-the-badge&logo=Git&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='MySql' src='https://img.shields.io/badge/my_sql-100000?style=for-the-badge&logo=MySql&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='xampp' src='https://img.shields.io/badge/xampp-100000?style=for-the-badge&logo=xampp&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='xampp' src='https://img.shields.io/badge/postman-100000?style=for-the-badge&logo=xampp&logoColor=white&labelColor=000000&color=000000'/></a>
<a href='https://github.com/shivamkapasia0' target="_blank"><img alt='Jira' src='https://img.shields.io/badge/Jira-100000?style=for-the-badge&logo=Jira&logoColor=white&labelColor=black&color=black'/></a>

## Thanks for reading!

Thanks for your attention, have a nice day! <3
