# Login e Registro Backend

Login e registro completo utilizando SpringBoot.

- [x] Spring Boot
- [x] Spring Security
- [x] Java Mail
- [x] Email verification
- [x] Spring Boot

## Requests
### CURL
```
curl --location --request POST 'localhost:8080/api/v1/registration' \
--header 'Content-Type: application/json' \
--data-raw '{
    "firstName": "TesteNome",
    "lastName": "NomeTeste",
    "email": "teste@gmail.com",
    "password": "senha"
}'
```