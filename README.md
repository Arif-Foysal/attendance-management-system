## Installing
To install the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/arif-foysal/attendance-management-system.git
   ```

2. Navigate to the project directory:
   ```bash
   cd attendance-management-system
   ```

3. Install the dependencies:
   ```bash
   composer install
   ```

4. Copy the `.env.example` file to `.env`:
   ```bash
   cp .env.example .env
   ```
>5. You need to update the `.env` file with your database credentials:
   ```env
   DB_DATABASE=attendance_management_system
   DB_USERNAME=root
   DB_PASSWORD=your_password_here
   ```

   Make sure to replace `your_password_here` with your actual database password.

6. Generate the application key:
   ```bash
   php artisan key:generate
   ```

7. Run the migrations:
   ```bash
   php artisan migrate
   ```

8. Start the development server:
   ```bash
   php artisan serve
   ```
