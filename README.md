<p align="left"><img src="https://www.webuffsolutions.com/assets/img/webuff_logo-small.png"></p>

# Student Management System

## Instructions

1. Follow the requirements as detailed below
2. It is not required for you to finish all the parts.

## Requirements:
  - Ability to login as admin (basic authentication using the command: "php artisan make:auth")

  Admin Account:
  - CRUD functionality (Create/ Read / Update / Delete) for: students

  Users:
  - admin (email: admin@gmail.com | password: p@ssw^rd)

  Roles:
  - admin

  Tables:
  - users table
  - roles table
  - students table
  
  Table Columns: (This is just a guide.. you can construct your own database schema)
  - roles ( id | name )
  - users ( id | role_id | name | email | password )
  - students ( id | user_id | student_no | lrn )

## Rules:
- Use Laravel make:auth as default Bootstrap-based design theme (Required)
- Use Laravel’s validation function, using Request classes (Optional)
- Use basic Laravel resource controllers with default methods – index, create, store etc. (Optional)

## Tips:
<p align="left"><img src="uploads/tips.PNG" height=100px; width=300px;></p>

## Pointers:
- Clearly written code is a big plus
- Bonus: Ajax Implementation, TDD, Repository Pattern, Us e of other frontend frameworks like semantic-ui, bulma-css, materialize css, etc
