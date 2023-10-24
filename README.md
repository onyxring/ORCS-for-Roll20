# OnyxRing Client Scripts for Roll20
This is a rollup of all individual "OnyxRing Client Scripts for Roll20".  These scripts are designed to be included in Roll20 character sheets, either individually or as a complete, client-side library.

If you are looking for the rollup of OnyxRing API scripts, you can find it [here](https://github.com/onyxring/ORAL-for-Roll20).

You may also be interested in the (ORAL ORCS repository](https://github.com/onyxring/Roll20OralOrcs), which includes both the "API Library" and the "Client Scripts" rollups, plus some additional modules which require code on both the server and in the client. 

Documentation for the individual, stand-alone scripts can be found in their corresponding repositories.

* [Roll20Async](https://github.com/onyxring/Roll20Async)      -  Enables attribute access while using JavaScript Promises and from within the callbacks of setTimeout() and setInterval().  Avoids the "Trying to do getAttrs when no character is active..." error message.
* [orcsCharacter](https://github.com/onyxring/orcsCharacter)    -  Introduces a significantly improved syntax for accessing the character's attributes, including Repeated Sections, via property objects.  Depends on the Roll20Async script.
