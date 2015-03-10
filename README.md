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
  * cached dir: ~/.nvm
* build tool - package manager: npm
  * cached dir: ~/.npm
* build tool - task runner: grunt
  * 
* dist tool:

* Javascript interpreter/runtime is named node (nodejs on some linux distros)

Perl
* env tool: perlbrew
  * cached dir:
* build tool:
  * default install dir: ~/perl5
* dist tool:
* packages repo: CPAN

Python:
* env tool:
  * pyvenv
* build tools:
  * easy_install
  * pip
* dist tool:
* packages repo: PyPi

Ruby:
* env tool: rbenv
  * cached dir: ~/.rbenv
* build tool:
* dist tool: capistrano (???)

Scala
All in one env+build+dist tools:
* sbt (written in scala-like dsl and scala, uses Apache Ivy for managing dependencies)
  * cached dir: ~/.ivy2
  * config files:
    * build.sbt
    * project/*.[sbt|scala]
  * download dependencies: sbt compile
  * make dist: sbt dist
  
* gradle (in groovy)
  * cache dir: ~/.gradle
  * example file: build.groovy
  
* maven (in xml)
  * cache dir: ~/.m2
  * example file: build.mvn
