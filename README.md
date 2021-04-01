# solution-azure-webapp
Bootstrap azure web application

* what for this solution
* deployment view
* limitations
  - snat limitations and self-managed vnet + nat [devblogs](https://devblogs.microsoft.com/premier-developer/reducing-snat-port-consumption-in-azure-app-services/) [docs](https://docs.microsoft.com/en-us/azure/app-service/troubleshoot-intermittent-outbound-connection-errors)

# Init basic infra

## Provider configuration and propagation

### terraservice concept
- what we are solving
- terraservice description + deployment view components
- workspace mappings
- provider generation

### 0_terraform_infra (example + code listing)

## Shared resources
- sharing criteria
- data format
- re-use examples

## Basic infra pipeline

- example of pipeline + BS + screenshots

## Quality gates basic infra

- SCA

# Application example (managed service based)
TBU

# Application example (container based)

## Artifact preparation

## Service deployment

## Release pipeline (azure devops based)
