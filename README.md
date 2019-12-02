# Pin-It-Up-App
A Django project to record varieties of work at a single place : to-do list (Todo), remainders (Remind Me) and systematizing task (Jot It Down).

## Installation
### Cloning repository
Clone the repository to download the project
```
>> git clone https://github.com/Shree987/PinItUp-App.git
>> cd PinItUp-App
```

### Creating Virtual Environment
Create a virtual envionment for the project
#### Windows
Install the virtual environment
```
>> pip3 install virtualenv
```
Create an instance
```
>> virtualenv -p python env
```
Activate the virtual environment
```
>> env\Scripts\activate
```

#### Ubuntu
Install the virtual environment
```
>> pip3 install virtualenv
```
Create an instance
```
>> virtualenv -p python env
```
Activate the virtual environment
```
>> source env/bin/activate
```
### Install Django
Install Django for the project. Ignore if it is already downloaded.
```
>> pip install django
```

### Migrations
Apply the migrations to create the tables in database.
```
>> cd myproject
>> python manage.py makemigrations
>> python manage.py migrate
```
*NOTE: Ignore the warning messages regarding URL*
### Server
Run the server to run project.
```
>> python manage.py runserver
```
