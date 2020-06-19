# arcli
Aids in creating stubs for CloudUp primitives (term, object, API, API endpoint method)

## Install


## Running


### Create Term

Defining a lexicon specific to your application is a key starting point for understanding.


### Create ARbject from Terms

The terms can then be used to define ActiveRules Objects (ARbjects) that represent larger concepts within your application as well as define the ontology of the terms and ARbjects.


### Create Handlers from ARbjects and Terms

Handlers define code that will act upon ARbjects.

Handlers can implement ActiveRules as well as be called by them.


### Create ActiveRules from ARbjects and Terms

Ther rules seprate business logic from the implementation code.


### Create API Spec from ARbjects and  Handlers that enforce ActiveRules

The ARbjects and ActiveRules can be inspected to create a valid OpenAPI spec.


### Define Deployment Environment

A deployment environment defines thta info Serverless requires to deploy an API


### Create Backend Infrastructure

The ARbjects and ActiveRules can be inspected to create databases, caches and other backend resources.


#### Publish REST API to Environment

An API Spec can be deployed to an environment.


### Publish Wesocket API to Environment

ARbjects and ActiveRules can also be inspected to create a WebSocket API using the same underlying handlers.