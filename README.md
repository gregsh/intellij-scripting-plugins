
IntelliJ Scripting Plugins
==========================
[![GitHub license](https://img.shields.io/badge/license-Apache%20License%202.0-blue.svg?style=flat)](http://www.apache.org/licenses/LICENSE-2.0)

Script engines for Java Scripting API (ex JSR-223) for IntelliJ-based tools.


Once the specific plugin is installed it becomes possible to use the corresponding language in:
* [IDE Scripting Console](https://www.jetbrains.com/help/idea/ide-scripting-console.html)
* [Database Data Extractors](https://www.jetbrains.com/help/datagrip/export-data-in-ide.html#creating-any-text-extractor-with) 
* [Database Schema Generators](https://www.jetbrains.com/help/datagrip/generating-code.html)


Clojure
=======

* [Plugin page](https://plugins.jetbrains.com/plugin/12469-intellij-scripting-clojure)
* Script engine: `org.clojars.ato:clojure-jsr223:1.5.1`, `org.clojure:clojure:1.12.0-alpha12`

Add `-Didea.mimic.jar.url.connection=true` in `Help | Edit Custom VM Options`.


JavaScript
==========

* [Plugin page](https://plugins.jetbrains.com/plugin/12548-intellij-scripting-javascript)
* [Script engine](https://github.com/graalvm/graaljs): `org.graalvm.js:js-scriptengine:23.0.4`, `org.graalvm.js:js:23.0.4`

Add `-Dpolyglot.js.nashorn-compat=true` in `Help | Edit Custom VM Options`.


Python
======

* [Plugin page](https://plugins.jetbrains.com/plugin/12471-intellij-scripting-python)
* [Script engine](https://github.com/jythontools/jython): `org.python:jython-standalone:2.7.4b2`

Add `-Didea.mimic.jar.url.connection=true` in `Help | Edit Custom VM Options`.
 

Ruby
====

* [Plugin page](https://plugins.jetbrains.com/plugin/12549-intellij-scripting-ruby)
* [Script engine](https://github.com/jruby/jruby): `org.jruby:jruby:9.4.7.0`

Add `-Dorg.jruby.embed.localcontext.scope=threadsafe` in `Help | Edit Custom VM Options`.



