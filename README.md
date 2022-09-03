# kubernetes-swagger-ui
This is an example deployment  of swagger-ui after generated jaxrs-api.json with [swagger-core-maven-plugin](https://mvnrepository.com/artifact/io.swagger.core.v3/swagger-maven-plugin) from resteasy api.

## How to Setup?
1 - Create namespace monitoring : `kubectl create ns ozgen`

2 - In the project directory:
` kustomize build k8s | kubectl apply -f -
`
Check & port-forwarding the swagger-ui deployed correctly or not ?




