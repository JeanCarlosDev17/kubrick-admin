---
stoplight-id: qdp6e163d99rb
tags: [autenticación]
---

# Autenticación

La autenticación se envía en cada request que se hace a la API, enviando un objeto llamado "auth", el cual, contiene "email" y "password", tal como se muestra en el siguiente ejemplo:

```json
"auth": {
  "email": "admin@kubrick.com",
  "password": "Password.secure.6"
}
```
