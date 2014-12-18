Common Interface Model
========

We use Swagger to determine the common interface. The entire network is made up of apps, and each app has two interfaces:

* Container - This is the API interface for managing the container itself.
* Instance - This is the API interface for whatever is running in the instance.

Here I will list out the container interface (which we really don't have yet), as outline, and as Swagger.

**Container Interface Model** { put swagger link when we have}
* process/
* logs/
* changes/
* export
* resize/
* start/
* stop/
* restart/
* kill/
* pause/
* unpause/
* attach/
* wait/
* remove/
* files/
* folder/
* data/
* backup/
* restore/

**Core Instance Interface Models**
* Org - http://org.api.stack.network/definitions/instance.json
* User - http://user.api.stack.network/definitions/instance.json
* Domain - http://domain.api.stack.network/definitions/instance.json
* App - http://app.api.stack.network/definitions/instance.json
* Instance - http://instance.api.stack.network/definitions/instance.json
* Server - http://server.api.stack.network/definitions/instance.json

All none core interface models will be defined within the app definition, in other section. This area is just for defining the container interface, and the instance interface for the core apps.
