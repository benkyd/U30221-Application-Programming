# Scrabble (Multiplayer)
## 2020/21 L4 Application Programming coursework

SEE BELOW FOR CONFIGURATION GUIDE

### Product Description

The following resources were used for the creation of the game's logic:
* https://scrabble.hasbro.com/en-us/rules
* https://www.zapsplat.com/?s=scrabble
* https://www.scrabble3d.info/t2342f139-Default-rules.html


The solution to locale-ise language in HTML is extremely naive and there are a lot better ways to do it, i did what i could in the time without a full refractor and SSR.
However it is not at much detriment of readability and maintainability of the code so i didn't deem it neccesary.

The locales are stored in different language files so it is easier for people to contribute and thus more maintanable.

If the scope allowed for it, every function would be (reasonably) unit tested. 

### Configuration Guide

Make sure your working directory is root/server

1. run ```npm i```
2. run ```npm run setup```
3. run ```npm run start```

If you want a custom port create a .env file and use the variable PORT
or just use environment variables

### Implementation Rationale


### Bugs and Issues

### Contributing

To contribute a translation 

### Acknowledgements

Express.js - HTTP Routing and Management
Socket.io - Socket Routing and Management
Inês Filipa Baiõa Antunes - Tranlations (Portuguese, Spanish)
