# Login Registration Backend 

# Pharmacy-POS-login-registration-backend system using Spring Boot.


- [x] Spring Boot
- [x] Spring Security
- [x] Java Mail
- [x] Email verification with expiry
- [x] Spring Boot

## Email verification link with expiry


## Example requests
### Postman


### CURL
```
curl --location --request POST 'localhost:8080/api/v1/registration' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "Wycliffe",
    "lastName": "Mwimali",
    "email": "joelwaks46@gmail.com",
    "password": "password"
}'
```

