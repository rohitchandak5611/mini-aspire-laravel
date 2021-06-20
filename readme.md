(A) MiniAspire - Laravel Project


The task is defined below:

 - Build a simple API that allows to handle user loans.
 - Necessary entities will have to be (but not limited to): users, loans, and repayments.
 - The API should allow simple use cases, which include (but are not limited to): creating a new user, creating a new loan for a user, with different attributes (e.g. duration, repayment frequency, interest rate, arrangement fee, etc.), and allowing a user to make repayments for the loan.
 

(B)Installation Instructions

- Run `composer install`
- Run `cp .env.example .env`
- Run `php artisan key:generate`
- Run `php artisan migrate`
- Run `php artisan passport:install`


(C)Third-party Packages Used

- [Laravel Passport](https://laravel.com/docs/passport)
