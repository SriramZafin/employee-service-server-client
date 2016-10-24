This server was generated by the swagger-codegen project. By using the OpenAPI-Spec from a remote server, you can easily generate a server stub. This is an example of building a swagger-enabled scalatra server.

 This example uses the scalatra framework. To see how to make this your own, look here:

 To generate the client side stubs :

1. Make sure the swagger specification is available at https://<>/api-docs/swagger.json
2. Download the swagger-codegen available at https://github.com/swagger-api/swagger-codegen
3. Build the project using "mvn package"
4. From this project location. generate the client stubs using the below command
 java -jar modules/swagger-codegen-cli/target/swagger-codegen-cli.jar generate -i https://<>/api-docs/swagger.json -l scala -o ../scala-employee-service-client

 where -l denotes the language for the reference implementation (Scalatra = Scala + Sinatra) -o denotes the output folder where the server stubs get generated
