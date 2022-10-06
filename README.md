# Mbaza-product github actions template
A repository that contains template necessary to build, deploy, run and maintain various mbaza-product applications
# Build and deploy to server
Usage: 
```
jobs:  
  build and deploy:
    uses: mbaza-product/infratructure.github.template/.github/workflows/build_and_deploy.yaml@main
    with: 
      PROJECT_ROOT_PATH: /usr/project
      ENVIRONMENT: self-hosted
      SERVICE_LOCATION_PATH: service
      NETWORK_NAME: external_docker_network_name
```
