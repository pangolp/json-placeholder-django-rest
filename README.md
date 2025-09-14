# json-placeholder-django-rest

![api_root](https://user-images.githubusercontent.com/2810187/91445225-399d7380-e84c-11ea-9e62-f7c583feb0bb.png)

![user_list](https://user-images.githubusercontent.com/2810187/91445255-4621cc00-e84c-11ea-9aad-3be91af4bbb1.png)

The repository contains JSON placeholder models, allowing for CRUD of said model and the ability to add your own data. The steps to deploy it are detailed below.

1. Create a virtual environment: `python3 -m venv .env`
2. Activate the environment: `source .env/bin/activate`
3. Install dependencies: `pip install -r requirements.txt`
4. Create tables: `python3 manage.py migrate`
5. Run the server: `python3 manage.py runserver`

## On Windows
- Instead of `python3`, use just `python`
- To activate the virtual environment: `.env\scripts\activate`

## URLS
- [x] /posts
- [x] /comments
- [x] /albums
- [x] /photos
- [x] /todos
- [x] /users
