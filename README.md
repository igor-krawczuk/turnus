# TURNUS

The latest Eclipse stable version can be downloaded from [http://turnus.co/eclipse/](http://turnus.co/eclipse/).
Please make srure to use the latest version of **Eclipse Neon** *for RCP and RAP Developers* that cen be downloaded from [here](http://www.eclipse.org/downloads/packages/eclipse-rcp-and-rap-developers/neon1a).

## Build from sources
If you want to build the latest version from the sources you should clone all the repositories and use maven to build the sources.

```
mkdir turnus
cd turnus
git clone https://github.com/turnus/turnus.git
git clone https://github.com/turnus/turnus.core.git
git clone https://github.com/turnus/turnus.orcc.git
git clone https://github.com/turnus/turnus.neo4j.git
git clone https://github.com/turnus/turnus.p2.git
cd turnus.p2
mvn install
```

# Contacts

Simon Casale-Brunet [casalebrunet [at] ieee [dot] org](mailto:casalebrunet@ieee.org)

