# Introduction

A starter repository is a location where Starters are stored and shared.  

A _starter repository_ contains an `index.yaml` file that contains an entry for each starter.  A starter is defined by referencing three objects,

* Code Repository:  The application code.  
* Generator: The generator that creates files to deploy the application.
* Actions: Actions to execute, e.g. create github repo.

## The starter repository structure

The top level `index.yaml` file contains information about each starter.

The directory `code` contains YAML files defining metadata about the application code repository.  
The directory `generators` contains YAML files defining metadata about the generator and what generator commands to execute
The directory `actions` contains YAML files for defining optional actions to execute when a starter is created.

All YAML files in each directory will be processed.


