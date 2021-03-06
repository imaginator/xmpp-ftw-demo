# XMPP-FTW (For The Web/Win) Demo/Examples

This repository runs a server which loads (xmpp-ftw)[https://github.com/xmpp-ftw/xmpp-ftw] and sets it up for experimentation/development.

The user is given acccess to both a demo system and the manual for `xmpp-ftw`.

For more information on `xmpp-ftw` please see https://xmpp-ftw.jit.su.

# Try it out...

The code is now up and running at https://xmpp-ftw.jit.su so you can try it out. Be aware that this 
setup is only for trying xmpp-ftw out and may be slow as we need to go client ↔ nodejitsu (east coast US) ↔  your XMPP server and back each time.

* https://xmpp-ftw.jit.su/manual -- XMPP-FTW manual
* https://xmpp-ftw.jit.su/demo -- Awesome demo tool, generated from manual

# Build status

[![Build Status](https://secure.travis-ci.org/xmpp-ftw/xmpp-ftw-demo.png)](http://travis-ci.org/xmpp-ftw/xmpp-ftw-demo)

# Components

XMPP-FTW is built up of smaller components (although is currently in tne process of bieng split).

The main module XMPP-FTW has code for login, roster, and presence as well as a few utilities that are used through most of XMPP.

* XMPP-FTW: [![Build Status](https://secure.travis-ci.org/xmpp-ftw/xmpp-ftw.png)](http://travis-ci.org/xmpp-ftw/xmpp-ftw)
* DISCO (XEP-0030): [![Build Status](https://secure.travis-ci.org/xmpp-ftw/xmpp-ftw-disco.png)](http://travis-ci.org/xmpp-ftw/xmpp-ftw-disco)
* Multi User Chat / MUC (XEP-0045)  [![Build Status](https://secure.travis-ci.org/xmpp-ftw/xmpp-ftw-muc.png)](http://travis-ci.org/xmpp-ftw/xmpp-ftw-muc)
* Jabber Search (XEP-0055)  [![Build Status](https://secure.travis-ci.org/xmpp-ftw/xmpp-ftw-search.png)](http://travis-ci.org/xmpp-ftw/xmpp-ftw-search)
* Publish-Subscribe / PubSub (XEP-0060)  [![Build Status](https://secure.travis-ci.org/xmpp-ftw/xmpp-ftw-pubsub.png)](http://travis-ci.org/xmpp-ftw/xmpp-ftw-pubsub)
* In-Band Registration (XEP-0077)  [![Build Status](https://secure.travis-ci.org/xmpp-ftw/xmpp-ftw-register.png)](http://travis-ci.org/xmpp-ftw/xmpp-ftw-register)
* Superfeedr  [![Build Status](https://secure.travis-ci.org/xmpp-ftw/xmpp-ftw-superfeedr.png)](http://travis-ci.org/xmpp-ftw/xmpp-ftw-superfeedr)
* buddycloud  [![Build Status](https://secure.travis-ci.org/xmpp-ftw/xmpp-ftw-buddycloud.png)](http://travis-ci.org/xmpp-ftw/xmpp-ftw-buddycloud)

* Item parser - builder and parser for "common" pubsub payloads
  * [![Build Status](https://secure.travis-ci.org/xmpp-ftw/xmpp-ftw-item-parser.png)](http://travis-ci.org/xmpp-ftw/xmpp-ftw-item-parser)

# Run the demos locally

* npm i xmpp-ftw-demo
* `cd node_modules/xmpp-ftw-demo && npm start`
* Go to `http://localhost:3000/`

To work on the code in 'development mode' (where process restarts as files change) run `npm run-script develop`.

# License

License is Apache 2.0, please let me know if this doesn't suit.
