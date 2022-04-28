# Middle Auth
Builds on top of [Go JWT Middleware](https://github.com/auth0/go-jwt-middleware) But 
provides middleware to be used specifically by [Fiber](https://docs.gofiber.io) and 
[Serverless AWS Lambdas](https://github.com/aws/aws-sdk-go-v2).

I wrote this because I did not want to use adapter to translate middleware, 
and I wanted more control of initialization and readability.