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