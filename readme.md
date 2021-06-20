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

(D) API Json
https://github.com/rohitchandak5611/mini-aspire-laravel/blob/master/Mini-aspire-laravel-api.json

(E) PHP version 7.1 +

(F) APi created for
1 ) User Registration 
(2) User Login - Authentication token
(3) Create new Loan - With Auth token
(4) List all loan as well user wise loan display- With Auth token
(5) Loan repayment -With Auth token

