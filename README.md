# JHipster Base

This project contains JSON definitions and schema files for JDL option data shared between JHipster Core and JHipster IDE products.

## Installation

```
$ npm install -g ajv-cli
$ npm install -g markdown-table-cli
```

## Build

```
$ git clone https://github.com/colameo/jhipster-base.git
$ cd jhipster-base
$ sh scripts/build.sh
```

## How to validate
- go to https://www.jsonschemavalidator.net/
- choose "Schema Draft v7" for the JSON schema
- copy/paste JSON schema and option files of this repo
- or use the above installed cli tool 'ajv-cli':
  ```
  ajv validate -s ./src/JDLApplicationOptions.schema.json -d ./src/JDLApplicationOptions.json
  ```
  or
  ```
  ajv validate -s ./src/JDLDeploymentOptions.json.schema.json -d ./src/JDLDeploymentOptions.json
  ```

## Description
The following tables are generated from JSON sources: 

- [Fields](JDLFields.md)
- [Options](JDLOptions.md)
- [Application Options](JDLApplicationOptions.md)
- [Deployment Options](JDLDeploymentOptions.md)
- [Languages](JDLLanguages.md)

