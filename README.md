# Tea-Shop App

```
This is a Mini E-Commerce project with a frontend built in React & Redux and a backend built in Django API.
Customers can login and order their favourite tea from the app
```

## Live Demo

**This App uses a Heroku free plan, so I am afraid that it takes time to load the pages.**

Check out [FRONTEND LIVE DEMO](https://frontend-teashop.herokuapp.com/) here!!

Check out [API LIVE DEMO](https://backend-teashop.herokuapp.com/) here!!





## Tech used

```
* Frontend : React & Redux
* Backend : Django
```

## How to Install

1. Git Clone

```
git clone https://github.com/Sam-Rai/Tea_Shop.git
```

2. Backend setting

```
cd backend
Python -m venv env
(For Mac) source env/bin/activate
(For Windows) env/Scripts\activate
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
# Open http://127.0.0.1:8000/posts/

# To have dummy data for testing run:
python manage.py fixtures/dummy-data.json
```

3. Frontend setting

```
cd frontend
npm install
npm start
# Open http://127.0.0.1:3000/
```
