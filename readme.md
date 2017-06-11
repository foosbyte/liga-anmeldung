# league-registration
## local env
### setup
1. you have to have an amazon aws account :-/. Otherwise you won´t be able to use the aws cli... 
2. download & install local dynamodb
3. download & install aws cli, e.g.: `brew install awscli `
    1. set default region: `aws configure`

### run
1. startup dynamodb, the following command will startup with a local single file database: `java -Djava.library.path=/Users/hannesthielker/opt/aws/dynamodb_local_latest/DynamoDBLocal_lib -jar /Users/hannesthielker/opt/aws/dynamodb_local_latest/DynamoDBLocal.jar -dbPath /Users/hannesthielker/var/opt/aws/dynamodb -sharedDb`






## local env next try ;-)
see: [example](https://github.com/serverless/examples/tree/master/aws-node-rest-api-with-dynamodb-and-offline)
1. npm install -g serverless



## further information
+ aws lambda auth [link](https://github.com/danilop/LambdAuth)
+ swagger intro [link](https://apihandyman.io/writing-openapi-swagger-specification-tutorial-part-1-introduction/)
+ swagger and jwt
    + [http://miguelduarte.pt/2017/04/19/using-jwt-authentication-with-swagger-and-node-js/]
    + [http://www.mimiz.fr/blog/use-authorization-header-with-swagger/]
    