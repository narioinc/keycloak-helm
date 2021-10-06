# Keycloak-helm
Keycloak helm charts

I created this keycloak helm chart after failing to run the ones hosted bitnami and codecentric repos.
Just clone this repo and create the keycloack instance in a desired namespace and you should be good to go

As of creation. I used the latest images of keycloak and postgres
keycloak: v15.0.2  (https://quay.io/repository/keycloak/keycloak/manifest/sha256:c0ce53904f3b5fabfdc0dfa6e53ec46a3c2adfb4818116b94cbdfc66539d1dd1)
postgres: v14.0  (https://github.com/docker-library/postgres/blob/db430ccd715678b60d7c7b9a0fee577991998837/14/bullseye/Dockerfile)

# Installation
1) clone this repo and execute the command below

* $> helm install keycloak ./keycloak-helm -n keycloak --create-namespace
