mdwiki-editor
=============

An editor for MDwiki(https://github.com/Dynalon/mdwiki)

Development Status
----------------------

Currently works. But without proper organization of code, without tests and documentation. Planning to refactor soon.

Installation
----------------

1. Install [node-webkit](https://github.com/rogerwang/node-webkit)
2. `cd` into the cloned repo and 

```
# installs dependency
npm install
npm install -g bower
bower install
#build
grunt
# run with `node-webkit`
nw .
```

Run tests
---------------

```
npm install jasmine-node -g
jasmine-node --coffee spec/
```

License
-----------------

MIT License, see LICENSE. Copyright (c) 2014 Utensil Song (https://github.com/utensil)

