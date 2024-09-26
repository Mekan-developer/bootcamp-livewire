# Project Name

> Brief description or tagline of the project.

[![Laravel Version](https://img.shields.io/badge/Laravel-11.9-red)](https://laravel.com)

## Table of Contents

- [About](#about)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## About

A detailed explanation of what your project does, its purpose, and why you built it.

## Features

- List major features of the project.
- Example: User authentication, Admin panel, Payment gateway integration, etc.

## Requirements

- PHP >= 8.1
- Laravel 11.x
- Composer
- MySQL or other database

## Installation

### 1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

## explaniation 

- I created policy named ChirmPolicy "by command php artisan make:policy ChirpPolicy --model=Chirp"
- I created notification named NewChiro "by command php artisan make:notification NewChirp"
- I created event named ChirpCreated  "by command php artisan make:event ChirpCreated"
- I created Listener named SendChirpCreatedNotifications  "by command php artisan make:listener SendChirpCreatedNotifications --event=ChirpCreated (I can not start work it(isledip bilmedim))"