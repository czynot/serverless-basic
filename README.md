# serverless-basic

### Creating an AWS NodeJS Serverless module
`serverless create --template aws-nodejs --path <path-name> --name <module-name>`

### Run the function locally
`serverless invoke local --function <function-name>`

### Deploy to Lambda and CloudFormation
`serverless deploy`

### Invoke the deployed function
`serverless invoke --function <function-name> --log`

### Use CURL to invoke an HTTP endpoint if defined
`curl <endpoint-url>`
