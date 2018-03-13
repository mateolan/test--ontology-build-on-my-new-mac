---
layout: ontology_detail
id: testeo
title: Test  ontology build on my new mac
jobs:
  - id: https://travis-ci.org/mateolan/test--ontology-build-on-my-new-mac
    type: travis-ci
build:
  checkout: git clone https://github.com/mateolan/test--ontology-build-on-my-new-mac.git
  system: git
  path: "."
contact:
  email: cjmungall@lbl.gov
  label: Chris Mungall
description: Test  ontology build on my new mac is an ontology...
domain: stuff
homepage: https://github.com/mateolan/test--ontology-build-on-my-new-mac
products:
  - id: testeo.owl
  - id: testeo.obo
dependencies:
 - id: bfo
 - id: ro
 - id: pato
tracker: https://github.com/mateolan/test--ontology-build-on-my-new-mac/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
---

Enter a detailed description of your ontology here
