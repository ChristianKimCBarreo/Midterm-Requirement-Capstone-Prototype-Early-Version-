# Midterm-Requirement-Capstone-Prototype-Early-Version-

Manpower Productivity Management System

ITE 116 Laravel Capstone Prototype

Group Members
Christian Kim C. Barreo

System Description
A web system where administrators assign tasks to employees, and employees update and submit their work for review.

User Roles
Admin: logs in, views the dashboard and employee list, creates and assigns tasks, monitors progress, and approves or rejects submissions.
Employee: logs in, views their own assigned tasks, updates progress, submits completed work, and sees the approval status.

Main Feature
Task assignment and completion management: the admin assigns a task, the employee submits it, and the admin approves or rejects it.

Demo Accounts
| Role | Email | Password |
| Admin | admin@example.com | password123 |
| Employee | employee@example.com | password123 |

Installation
1. Create an empty MySQL database named `manpower_productivity`.
2. Run:

bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd manpower-productivity
composer install
npm install
copy .env.example .env
php artisan key:generate
php artisan migrate --seed
npm run build
php artisan serve

3. Open http://127.0.0.1:8000

