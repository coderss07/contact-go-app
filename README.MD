# Simple Contact saving App

## I have used postgresSQL for database

postgressql server: 5432

Project server: 8000

## Api:

### localhost:8000/api/user/new :

for registering new user

Json: {"email": "sarthu858@gmail.com", "password": "******"}

### localhost:8000/api/user/login :

for login user

Json: {"email": "sarthu858@gmail.com", "password": "******"}

### localhost:8000/api/contacts/new :

for adding new contact by id = user_id

Json: {"user_id": 1, "name": "sarthu", "phone": "9411741378"}

### localhost:8000/api/me/contacts :

for displaying all contacts by id = user_id

Json: {"user_id": 1}



