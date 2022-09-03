# kubernetes-swagger-ui
This is an example deployment  of swagger-ui after generated jaxrs-api.json with [swagger-core-maven-plugin](https://mvnrepository.com/artifact/io.swagger.core.v3/swagger-maven-plugin) from resteasy api.
Resteasy example project can be found in [this](https://resteasy.dev/2020/05/22/swagger/) or [that](https://github.com/resteasy/resteasy-examples/tree/main/jaxrs-swagger-example) links.

## How to Setup?
1 - Create namespace monitoring : `kubectl create ns ozgen`

2 - In the project directory:
` kustomize build k8s | kubectl apply -f -
`
Check & port-forwarding the swagger-ui deployed correctly or not ?




