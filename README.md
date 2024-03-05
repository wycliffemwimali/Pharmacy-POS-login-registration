# Login Registration Backend 

# Pharmacy-POS-login-registration-backend system using Spring Boot.


- [x] Spring Boot
- [x] Spring Security
- [x] Java Mail
- [x] Email verification with expiry
- [x] Spring Boot

## Email verification link with expiry

![emailverification](https://github.com/wycliffemwimali/Pharmacy-POS-login-registration-backend/assets/99508839/1de1457d-1b02-4b3d-b4c6-49c366a6bb41)

## Example requests
### Postman
![examplerequests](https://github.com/wycliffemwimali/Pharmacy-POS-login-registration-backend/assets/99508839/cd3bdd60-0b1f-4634-b93f-76e27ff9bd9a)

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

