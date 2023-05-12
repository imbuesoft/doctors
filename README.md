# doctors - v1
create migration (database table) // php artisan make:migration create-table-doctors
table:doctors
- name(string,50)
- experiance(string,20)
- speciality(string,30)
- image(string)
- registration_no(string,20)
- address(string)
- mobile(bigint)
- email(string,100)
model doctor // php artisan make:model Doctor
controller // php artisan make:controller doctorcontroller

CRUD - Doctor

