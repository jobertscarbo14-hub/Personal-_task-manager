# Personal Task Manager

- **Project Code:** WST21-PM-2026-SF
- **Student Name:** [CARBO JOBERT]
- **Course & Year:** [BSIT-2ND YEAR, SECTION-7]
- **Database Used:** SQLite (default); MySQL can be configured in `.env`.

## About

A beginner-friendly Laravel project for keeping personal tasks in one place. It uses routes, a controller, an Eloquent model, database migrations, and Blade views.

## Features

- Add Task
- View Tasks
- Edit Task
- Delete Task
- Update Status between Pending and Completed
- Dashboard counts for all, pending, completed, and overdue tasks
- Filter the task list by status
- Mark past-due pending tasks

## Requirements

- PHP 8.3 or newer
- Composer
- SQLite PHP extension, or a MySQL database

## Setup

```bash
composer install
cp .env.example .env
touch database/database.sqlite
php artisan key:generate
php artisan migrate
php artisan serve
```

Open `http://127.0.0.1:8000` in a browser. The task list starts empty, ready for your own tasks.

To use MySQL instead, update `DB_CONNECTION`, `DB_HOST`, `DB_PORT`, `DB_DATABASE`, `DB_USERNAME`, and `DB_PASSWORD` in `.env`, then run the migrations.

## Screenshots

![alt text](image.png)
