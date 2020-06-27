# AuthenticationSSO


Use following service to generate token 
http://localhost:9080/signin

provide json formated below data 

{
    "username": "user",
    "password":"password"
}

currently username and password is hardcoded


user below service to verify token 

http://localhost:9080/token
provide generated token as bearer token 


Note currently the time 5 min is hardcoded couldn't complete it due to time constraint.
