# Using Django ORM only without web server

## Detail Guide
[Using Django ORM only without web server]()

## Requirements
- Python 3.10.11
- Django 4.0.4

## Setup
```cmd
git clone https://github.com/ivanyu199012/16-DjangoUsedOrmOnly.git
cd 16-DjangoUsedOrmOnly

python -m venv ormOnlyEnv
ormOnlyEnv\Scripts\activate

pip install -r requirements.txt
```

## Create sqlite database
```cmd
python manage.py migrate
```

## Run
```cmd
python main.py
```

## Output
```cmd
Project started!!
Saved!!
```
![image](https://cdn.hashnode.com/res/hashnode/image/upload/v1713607599225/1287bd5c-1472-42d2-bb41-9ecc4846564f.png)
