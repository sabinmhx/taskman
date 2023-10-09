# taskman

# Task Management App in Laravel

This is a simple Task Management web application built with Laravel, designed to help users organize and keep track of their tasks. Whether you're a developer, a student, or just someone trying to stay organized, this app will help you manage your tasks efficiently.

## Features

- **Task Creation:** Users can create tasks, set deadlines, and assign them to specific categories.
- **Task Management:** Users can view, edit, and delete their tasks. They can also mark tasks as completed.
- **Category Management:** Users can create, edit, and delete task categories to better organize their tasks.

## Installation

Follow these steps to set up the Task Management App in your local environment:

1. Clone the repository:

    ```
    git clone https://github.com/sabinmhx/taskman
    ```
2. Install Composer Dependencies:

    ```
    composer install
    ```
3. Create a .env file by copying the example:

    ```
    cp .env.example .env
    ```
4. Generate an application key:

    ```
    php artisan key:generate
    ```
5. Set up your database configuration in the .env file.

6. Run the database migrations:
   
    ```
    php artisan migrate
    ```
7. Start the development server:
    
    ```
    php artisan serve
    ```
8. Access the application in your web browser at http://localhost:8000.

## License

This project is licensed under the [MIT License](LICENSE).
