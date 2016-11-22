# TURNUS

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0) [![Build Status](https://travis-ci.org/turnus/turnus.svg?branch=master)](https://travis-ci.org/turnus/turnus) 

The Eclipse plugins can be downloaded from this repository:
```
http://turnus.co/eclipse/
```
Please make sure to use the latest [Eclipse Neon](http://www.eclipse.org/downloads/packages/eclipse-rcp-and-rap-developers/neon1a) *for RCP and RAP Developers*.

## Build from sources
If you want to build the latest version from the sources you should clone all the repositories and successively use maven to build all the plugins. Here an example:

```
mkdir turnus
cd turnus
git clone https://github.com/turnus/turnus.git
git clone https://github.com/turnus/turnus.core.git
git clone https://github.com/turnus/turnus.orcc.git
git clone https://github.com/turnus/turnus.p2.git
cd turnus.p2
mvn clean install
```

# Contacts

Simon Casale-Brunet [casalebrunet@ieee.org](mailto:casalebrunet@ieee.org)

