# ABAP Platform CI/CD Samples
The ABAP Environment pipeline makes use of APIs of the SAP Cloud Platform (esp. cf cli) and the SAP Cloud Platform ABAP Environment (Projectname Steampunk). While the pipeline contains a fixed set of steps and stages, it is possible to adapt it using different configurations. This repository shows and explains different examples of these configurations. 

## Requirements
To create the examples shown in this repository yourself a Jenkins server and the entitlements for a SAP Cloud Platform ABAP Environment are required.

## Configuration
Please have a look at the [documentation of the piper project](https://sap.github.io/jenkins-library/pipelines/abapEnvironment/introduction/) to learn more about the configurations necessary to run the examples in this repository.

## How to use this repository

A Jenkins pipeline is defined by a "Jenkinsfile" and other pipeline specific configuration files. The examples in this repository consist of all required files for a specific use case. 

If you want to recreate a specifc use case, you can copy the associated files and replace the context specifc values (API Endpoints, Jenkins Credential IDs etc.)

## Examples

* [Running ATC checks on a transient ABAP Environment system]()
* Running ATC checks on a static ABAP Environment system
 
## Known Issues
A list of known issues is available on the GitHub issues page of this repository
