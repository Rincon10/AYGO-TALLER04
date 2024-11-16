# AYGO-TALLER04

## AWS Serverless Application Model
Click on [AWS Serverless Application Model](https://aws.amazon.com/es/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/) to open the resource.
 
### Arquitectura propuesta

![alt text](docs/images/01.png)


## Módulo 1: alojamiento web estático con implementación continua

Para comenzar, configurará AWS Amplify para alojar los recursos estáticos de la aplicación web con implementación continua integrada.

para copiar el repositorio usamos el siguiente comando
```bash
aws s3 cp s3://ttt-wildrydes/wildrydes-site ./ --recursive
```

## Habilitar AWS Amplify
A continuación, utilizará la consola de AWS Amplify para implementar el sitio web que acaba de confirmar en Git. La consola de Amplify se encarga de configurar un lugar para almacenar el código de la aplicación web estática y proporciona varias capacidades útiles que simplifican el ciclo de vida de la aplicación y permiten las prácticas recomendadas

![alt text](docs/images/02.png)



## Módulo 2: administrar usuarios

Creará un grupo de usuarios de Amazon Cognito para administrar las cuentas de los usuarios.
Información general

En este módulo va a crear un grupo de usuarios de Amazon Cognito para administrar las cuentas de los usuarios. Implementará páginas que permiten a los clientes registrarse como nuevo usuario, verificar su dirección de correo electrónico e iniciar sesión en el sitio.