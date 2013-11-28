````
alias: Site Updates
weight: 3
layout: docs
clearance: -1
title: CMEP Contribution Documentation
author: Mike Pearson
acknowledgementText: So long and thanks for all the fish.
keywords:
  - updates

````

Site Updates
----

### A reminder

>The site code lives in [CMEP-site](https://github.com/CMEPorg/CMEP-site), but the site sources live in [CMEP-sources](https://github.com/CMEPorg/CMEP-sources). 

You will have created a copy of CMEP-site and CMEP-sources on your local machine, side-by-side in the same parent folder using the commands such as:

```
mkdir CMEP
cd CMEP
git clone https://github.com/CMEPorg/CMEP-site.git
git clone https://github.com/CMEPorg/CMEP-sources.git
```

While the site is under development -- and that is unlikely to stop any time soon -- you will need to keep your local CMEP-site code up to date as well as updating the content from CMEP-sources.

### Updating CMEP-sources

```
cd CMEP-sources
git pull
```

### Updating CMEP-site
```
cd CMEP-site
git pull
npm update
bower update
./scripts/compile
```

`npm update` updates libraries used to make the server code whenever any new library has been referenced.

`bower update` similarly updates libraries used by client code - i.e. javascript libraries used by the browser.

`./scripts/compile` compiles LiveScript code into javascript. If you see problems with missing javascripts (`.js` files) when running `grunt server` it's likely to be because you have not compiled them. 
