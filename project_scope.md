- Project Small description: Formulário de login com autenticação via Ajax

- Techs: HTML5, CSS, JavaScript

- Specs: Auth via API utilizando Ajax.

- To do: After logged, need show a modal, or alert with the user details (show a diferent message for each user_type)

- Endpoint Response: 


#### In error case
```
{
    "error": true,
    "status_code: XXX, 
    "error_message": "something"
}
```

#### In success case
```
{
    "error": false,
    "status_code: 200, 
    "user": {
        "name":"string",
        "email" "string",
        "user_type": INT //1=admin, 2=editor, 3=writer
    },
    "token": "XXXXXXXXXXXXXXXXXXXXXX"
}
```
