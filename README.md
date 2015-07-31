# potential-hipster

**Still a work in progress**

tl;dr - Objectified client SDK's that make integration with applications much more pleasing :)


## Introduction and Problem

Currently, most client libraries offered are simply wrappers around the REST API and requires the user to have a very deep understanding about the API. Given this, it is hard for a user to start development for their applications and projects. As well, because the client libraries are just wrappers, there is no other added benefits other then just having assistive methods to do HTTP requests.

## Proposed Solution

Instead of wrapping the REST API in native languages, potential-hipster will provide an object-orientated architecture for SDK's with a focus on client-side languages. This will assist in illustrating the backend and providing users an easier way to use the our infrastructure as their backend from their applications. With these easily integrable client SDK's, we allow the users to just focus on the user experience for their applications and not on the infrastrcture.

Additionaly, but not in the main scope of the project, potential-hipster's architecture will include a full suite of assistive features for the SDK's. The following lists out possible additional features:
* Deeper support for client-side frameworks such as React / React Native, Backbone.js
* Real-time syncing of data and deliving real time updates to clients
* Offline support and disk persistence

## Usage
Everythign in the backend has a template, so the client would need to instantiate subclass to start interacting with items in that template:
```javascript
var Accounts = Podio.Template.extend({templateID: templateID, className: 'Accounts');
var account = new Accounts();
```
Given this class and instance, we can set parameters like so:
```javascript
account.set('name', 'Random Name');
account.set('email', 'random@email.com);
```
We can save like so:
```javascript
account.save(...)
```
Get an item in the template like so:
TODO

## Architecture
A work in progress, but currently, diagram exists here :)
https://www.lucidchart.com/invitations/accept/7825e77a-f272-493a-819b-5af6a94ed57f

