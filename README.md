# Task to Test Junior Laravel Developer Skills

### Basically, u'll need to bring a small project to manage companies and their employees. Mini-CRM.

**There are a few steps to accomplish this task:**
* Basic Laravel Auth: ability to log in as administrator.
* Use database seeds to create first user with email admin@admin.com and password “password”.
* CRUD functionality (Create / Read / Update / Delete) for two menu items: Companies and Employees.
* Companies DB table consists of these fields: Name (required), email, logo (minimum 100×100), website.
* Employees DB table consists of these fields: First name (required), last name (required), Company (foreign key to Companies), email, phone.
* Use database migrations to create those schemas above.
* Store companies logos in storage/app/public folder and make them accessible from public.
* Use basic Laravel resource controllers with default methods – index, create, store etc.
* Use Laravel’s validation function, using Request classes.
* Use Laravel’s pagination for showing Companies/Employees list, 10 entries per page.
* Use Laravel make:auth as default Bootstrap-based design theme, but remove ability to register.

*Also a point is to not use 3rd party packages in this project. Well, laravelcollective/html it’s allowed and also guzzle but another package to solve the problem with files or another stuff is prohibited.*

### Extra Task for “Advanced” Juniors
**If you feel like this task is too small and simple, you can add these things on top:**

* Use Datatables.net library to show table – with our without server-side rendering.
* Use more complicated front-end theme like AdminLTE.
* Email notification: send email whenever new company is entered (use Mailgun or Mailtrap).
* Make the project multi-language (using resources/lang folder).
* Basic testing with phpunit.
