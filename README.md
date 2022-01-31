## Desafio-java


##REPOSITORIO GITHUB

https://github.com/kerne/desafio-java


##ENDPOINTS

## REGISTRAR USUARIO

https://concrete-solutions-challenge.herokuapp.com/desafio-java/app/register
´´´json
JSON :
 {
        "name": "Juan Rodriguez",
        "email": "juan@rodriguez.org",
        "password": "hunter2",
        "phones": [
            {
                "number": "1234567",
                "citycode": "1",			
                "contrycode": "57"
            }
        ]
}
´´´
## LOGIN USUARIO

https://concrete-solutions-challenge.herokuapp.com/desafio-java/app/login

{
    "username": "juan@rodriguez.org",
    "password" : "hunter2"
}

## PROFILE USUARIO

https://concrete-solutions-challenge.herokuapp.com/desafio-java/app/concrete/profile/53d46ddd-74cb-4f5d-9780-df8729f22b07

agregar en header 
X-auth-token : {TOKEN GENERADO}


