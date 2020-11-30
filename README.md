## hapi-fhir-jpa-keycloak-docker
This [docker-compose](https://github.com/IntelliSOFT-Consulting/hpi-fhir-jpa-keycloak-docker/blob/main/docker-compose.yaml) deploys containers for HAPI-FHIR-JPA-SERVER (port: 8080), keycloak (port: 9090), and hapi-fhir authentication (port: 8084).

 * Check the configuration values at the environment (.env) file. Put `OAUTH_ENABLE=true` to protect the API. You can customize to suite your needs
 * Spin it up using `docker-compose up -d`
 * Wait a couple of minutes until the stack is deployed.
 Check the logs with `docker logs --details hapi-fhir`
