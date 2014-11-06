
rhaboo
------

Easy, accurate and fast local storage.

Has extensive automatically generated tests.

Details at http://rhaboo.org
 
parunpar
--------

A functional serialiser. 

Use this when you know exactly what you're encoding and how the serialised version should look. 

A parunpar includes both the encoder and the decoder for something. This library provides combinators for building bigger parunpars out of smaller ones.

ajon
----

Spun out of rhaboo tests. JSON-like serialiser but more accurate. Not fast at all.

evon
----

More interesting JSON-like serialiser. 

An evon encoding is a JS expression that's executed with eval() to restore the object. 

Unlike JSON, it supports the full variety of JS objects, including circular references, multiple references to the same object, prototypes, constructors and their parameters, various types of untruthyness, etc. 

It's surprisingly fast and will form the basis of the next version of rhaboo.

obtotype
--------

WIP repo about uses of JS prototypes other than inheritance.

digilife
--------

VM to enable free evolution of useful software in which programs can only survive by earning money (from humans or other programs) to rent computing resources on which to exist.  There are no other restrictions on their evolutionary strategy, but a nursery phase is planned during which they'll be taught some basic life skills.




