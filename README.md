# potential-hipster

tl;dr - Objectified client SDK's that make integration with applications much more pleasing :)

## Introduction and Problem

Currently, most client libraries offered are simply wrappers around the REST API and requires the user to have a very deep understanding about the API. Given this, it is hard for a user to start development for their applications and projects. As well, because the client libraries are just wrappers, there is no other added benefits other then just having assistive methods to do HTTP requests.

## Proposed Solution

Instead of wrapping the REST API in native languages, potential-hipster will provide an object-orientated architecture for SDK's with a focus on client-side languages. This will assist in illustrating the backend and providing users an easier way to use the Podio infrastructure as their backend from their applications. With these easily integrable client SDK's, we allow the users to just focus on the user experience for their applications and not on the infrastrcture.

Additionaly, but not in the main scope of the project, potential-hipster's architecture will include a full suite of assistive features for the SDK's. The following lists out possible additional features:
* Deeper support for client-side frameworks such as React / React Native, Backbone.js
* Real-time syncing of data and deliving real time updates to clients
* Offline support and disk persistence
