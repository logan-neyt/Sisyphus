# Sisyphus
Tournament ladder/rankings and bracket system.

## Running
### Live Coding
Running the application in Quarkus' dev mode will automatically deploy changes as you code.

```shell script
./mvnw compile quarkus:dev
```

Additionally running in dev mode will expose a Swagger UI page at `http://localhost:8080/q/swagger-ui`.

## API
### OpenAPI
OpenAPI exposed at `/q/openapi`.
### Metrics
Micrometer metrics are exposed at `/q/metrics`.