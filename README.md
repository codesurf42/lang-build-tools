# lang-build-tools
### Managing environments and building tools across languages

To sum up some common tools / operations across languages

Tools to manage multiple, independent environments on a single machine (env tool)
Tools to download and build needed dependencies for current environment/application (build tool)
Tools to pack current environment into a single file as a preparation to deploy (dist tool)

## Java
maven, groovy, ant

## Javascript
* env tool: nvm
  * cached dir: ~/.nvm
* build tool - package manager: npm
  * cached dir: ~/.npm
* build tool - task runner: grunt
  * 
* dist tool:

* Javascript interpreter/runtime is named node (nodejs on some linux distros)

## Perl
* env tool: perlbrew (http://perlbrew.pl/) (http://search.cpan.org/~gugod/App-perlbrew/bin/perlbrew)
  * cached dir:
* build tool:
  * default install dir: ~/perl5
* dist tool: PAR (https://metacpan.org/search?q=PAR)
* packages repo: CPAN (www.cpan.org)

## Python: 
(https://python-packaging-user-guide.readthedocs.org/en/latest/current.html)
* env tool:
  * pyvenv
* build tools:
  * easy_install
  * pip
* dist tool:
* packages repo: PyPi

## Ruby:
* env tool: rbenv
  * cached dir: ~/.rbenv
* build tool:
* dist tool: capistrano (???)

## Scala
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
