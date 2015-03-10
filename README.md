# lang-build-tools
Building tools across languages

To sum up some common tools / operations across languages

Tools to manage multiple, independent environments on a single machine (env tool)
Tools to download and build needed dependencies for current environment/application (build tool)
Tools to pack current environment into a single file as a preparation to deploy (dist tool)

Java
maven, groovy, ant

Javascript
* env tool: nvm
* build tool: node (named nodejs on some linux distros)
* dist tool:

Perl
* env tool: perlbrew
* build tool: 
* dist tool:

Python:
* env tool: 
  * easypython
  * pypy

Ruby:
* env tool: rbenv
* build tool:
* dist tool:

Scala
All in one env+build+dist tools:
* sbt (written in scala-like dsl and scala)
  * cached downloads in ~/.ivy2
  * example file:
  
* gradle (in groovy)
  * cache dir: ~/.gradle
  * example file:
  
* maven (in xml)
  * cache dir: ~/.m2
