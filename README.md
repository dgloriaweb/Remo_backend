# Remo backend

Solely backend endpoint with Sanctum authentication that returns token.

## install and run laravel server on docker

Use sail up -d

## create and test login endpoints in postman

POST `http://127.0.0.1:8083/api/register`
body: `{ "name": "Sec", "email": "sec@here.now", "password": "...", "password_confirmation": "..." }`

Then:
POST `http://127.0.0.1:8083/api/auth`
body: `{ "email": "sec@here.now", "password": "..." }`

## endpoints

### add suggestion
POST suggestion

### admin area
GET ideas top 10 by most voted

# Remo_backend
# Remo_backend


### TODO

Add user_group to user
