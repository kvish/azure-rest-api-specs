# Azure Migrate 
    
> see https://aka.ms/autorest

This is the AutoRest configuration file for Azure Migrate.

---
## Getting Started 
To build the SDK for Migrate, simply [Install AutoRest](https://aka.ms/autorest/install) and in this folder, run:

> `autorest`

To see additional help and options, run:

> `autorest --help`
---

## Configuration



### Basic Information 
These are the global settings for the API.

``` yaml
openapi-type: arm
tag: package-2018-02
```


### Tag: package-2018-02

These settings apply only when `--tag=package-2018-02` is specified on the command line.

``` yaml $(tag) == 'package-2018-02'
input-file:
- Microsoft.Migrate/2018-02-02/migrate.json 
```