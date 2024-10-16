# ptarp

__physical transportation accompany and relay protocol__ (ptarp) is a protocol to accompany and manage relays of physical transportations. ptarp should accompany transportations of physical goods with multiple, different and independent carriers, using this same protocol. No carrier must deliver to the final receiver, but bring it a little bit closer.

ptarp transports must get accompanied with an virtual document, defined with an identifier (URI) (e.g. ptarp.example.com/1234). this document must get updated by every carrier (currentHolder).


Fields of a ptarp document:

* active: is this transport still to move, or has ist arrived (bit)
* origin: startpoint (location)
* destination: is the localisation where to bring the transport 
* sender: person (local user or user@server)
* recipient: person who recives can close (active no) the transport    
* author: author and sender is differrent, to send things on behalf
* currentHolder: carrier currently transporting or holding
* currentLocation: carrier currently holding and wating the transport (optional while transporting) 
* contentDescription: text description (optional)
* contentSize: standard: EUR-pallet (EN 13698), Euro container: summ of length, with height
* contentWeight: max weight in kg
* contentClass:
  * people
  * food
  * warm food
  * non food
  * garbage
  * laundry
* priority: adress its quality of service from 1 to 100
* log: flat dump of hops

## Location

Locations can be defined by:
* common and __plain old geography address__ (e.g. 'Bob Doe, 123 Fake Street, 12345 Springsfield')
* __geolocation__ with coordinates, are difficult to translate to humans and for routing.

Or use an __URI__ ('bob@example.com') with an extra TXT DNS Record with a geography adress or a geolocation.


## Missing features

This does not (yet) support:

* versioning of travellog: like IP, I dont care where my packet was, only where it is, and where to go. Tracking and Tracing should be on another layer. 
* time to live? could be useful to avoid ghost shipments
* trusting: could be useful to request trust
* routing: every hop shold do its own routing
* payment: another layer

## Similar

* my own approach [Netzlogistik](http://regionales-wirtschaften-wiki.de/Netzlogistik) (in german)
