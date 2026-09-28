# Laravel Beginner Lab 1 — Mohammad Yaqoob Arif

**Faculty:** Faculty of Computer Science, Kabul University  
**Course:** Web Information Systems  
**Student Name:** Mohammad Yaqoob Arif  
**Student ID:** 34  
**Laravel:** 12.x  
**Lab Date:** 28 September 2026

## Lab Tasks Completed

- Task 1: PHP and Composer preparation
- Task 2: Laravel 12 project creation
- Task 3: Blade home page
- Task 4: `/` route and course variable
- Task 5: Custom `/about` page with navigation links
- `.env.example` configured for file-based session and cache
- Understanding questions answered in `docs/answers.md`
- Submission checklist included in `docs/submission-checklist.md`

## Run the Project

Requirements:
- PHP 8.2 or newer
- Composer
- Laravel 12
- Windows + Command Prompt/PowerShell

### 1. Install dependencies

From the project folder:

```bash
composer install
```

### 2. Create environment file

Windows CMD:

```cmd
copy .env.example .env
```

PowerShell:

```powershell
Copy-Item .env.example .env
```

### 3. Generate application key

```bash
php artisan key:generate
```

### 4. Clear configuration

```bash
php artisan config:clear
```

### 5. Start Laravel

```bash
php artisan serve
```

Open:

- Home: http://127.0.0.1:8000/
- About: http://127.0.0.1:8000/about

## Important

The lab instructions specify that Apache and MySQL do not need to be running for these basic Blade pages. The project uses file-based session/cache settings and does not require a database for the lab.

## GitHub Upload

Do not upload `.env`, `vendor/`, or other generated/local files. This repository includes `.gitignore` for that purpose.

Suggested repository name:

`laravel-beginner-lab-mohammad-yaqoob-arif`

## Official References

- https://laravel.com/docs/12.x/installation
- https://laravel.com/docs/12.x/views
- https://laravel.com/docs/12.x/routing
- https://getcomposer.org/doc/00-intro.md
