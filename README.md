# Reproduction repo for https://github.com/filamentphp/filament/issues/13779

- Clone the repo
- Composer install, run migrations, seed the db
- Go to the user resource in the admin panel
- Create a new user
  - In the first step, input the name and the email and then press Enter
  - I would expect it to go to the next step, but it tries to submit the form
