

# Description

eCommerce website like Amazon

## Features

- Shoppin Cart
- Product reviews and ratings
- Top products on display
- Product pagination

<br>


## Live demo

Live demo of the app is hosted on Heroku.  
Visit [https://amacloneapp.herokuapp.com/]

Test users credentials:

> Admin user
>
> - login - _admin@example.com_
> - password - _123456_

> Regular user
>
> - login - _k@example.com_
> - password - _123456_

_Due to demo reasons and heroku free terms, if an app receives no web traffic in a 30-minute period, it will sleep. Therefore, during the first launch, the application may take longer to load than usual, approximately 15 - 20 seconds. So please be patient and wait for the app to launch. Subsequent launches will be relatively fast._
heroku create -a example-app
## Technology stack

> ### FrontEnd
>
> - React
> - React Hooks
> - Redux with Hooks
> - React router
> - React bootstrap
>
> ### BackEnd
>
> - Node
> - Express
> - JWT
> - MongoDB
> - PayPal API
> - Heroku hosting
>   <br>





<br>
### Env Variables

Create a .env file in then root and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'secret'
PAYPAL_CLIENT_ID = your paypal client id
```

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```
# Run frontend (:3000) & backend (:5000) in the route file
npm run dev
# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```



### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```
# Import data
npm run data:import
# Destroy data
npm run data:destroy
```

```
Sample User Logins
admin@example.com (Admin)
123456
kk@example.com (Customer)
123456
jj@example.com (Customer)
123456
```