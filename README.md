# First Task

Follow the steps below and get some hands on practive with django migrations.


## Setup
- Clone the Repository
- run poetry install
- poetry run python manage.py runserver 0.0.0:8000

## Steps
- Run initial migrations
- Create A super user
- Login to the admin and create a person and a company.
- Add a new field (age) with a default to the Person model without a default value
- Migrate your People app
- Login to the admin again and check on the previous person.
- Add a new ForiegnKey to Company with a default value
- Add a new field (Industry) to the company model with a default
- Migrate your company app
- Create a new field on person called Department
- Delete the field for age from person
- Clear migrations and regenerate them.
- Bonus: Make the default on the company field of the person model dynamically use the first company in the database.

