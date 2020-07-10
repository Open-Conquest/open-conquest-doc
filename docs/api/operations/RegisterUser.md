---
id: registerUser
title: registerUser
sidebar_label: registerUser 
---

RegisterUserRequest
```json
{
	"credentials": {
		"type": "UserCredentials"
	},
	"password": {
		"type": "string"
	}
}
```

UserCredentials
```json
{
  "username": {
    "type": "string"
  },
  "password": {
    "type": "string"
  }
}
```

RegisterUserResponse
```json 
{
  "username": {
    "type": "string"
  },
  "token": {
    "type": "JWT"
	}
}
```
