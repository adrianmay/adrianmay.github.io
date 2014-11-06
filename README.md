
rhaboo
------

Easy, accurate and fast local storage.

Has extensive automatically generated tests.

Details at http://rhaboo.org
 
evon
----

JSON-like serialiser but much more accurate and pretty fast. 

An evon encoding is a JS expression that's executed with eval() to restore the object. 

Unlike JSON, it supports the full variety of JS objects, including circular references, multiple references to the same object, prototypes, constructors and their parameters, various types of untruthyness and sparseness, etc. 

For instance:

```_(_(_(h[0]=new Horse(2),'stable',2),'name',"dobbin"),'bettingOn',h[0])```

encodes a derived object which needs to be constructed with the parameter 2 to cause side effects outside of the object with three properties one of which is a reference to the object itself.

It's surprisingly fast and will form the basis of the next version of rhaboo.

parunpar
--------

A functional serialiser. 

Use this when you know exactly what you're encoding and how the serialised version should look. 

A parunpar includes both the encoder and the decoder for something. This library provides combinators for building bigger parunpars out of smaller ones.

This is the basis of the current rhaboo, but will probably not be used in the evon-based version.

ajon
----

JSON-like serialiser but more accurate. Not fast at all.

Used in rhaboo auto-generated test scripts to describe expected results. 

obtotype
--------

Research about uses of JS prototypes other than inheritance. Very WIP.

digilife
--------

VM to enable free evolution of useful software in which programs can only survive by earning money (from humans or other programs) to rent computing resources on which to exist.  There are no other restrictions on their evolutionary strategy, but a nursery phase is planned during which they'll be taught some basic life skills.




