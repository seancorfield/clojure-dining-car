**Clojure Dining Car**

*A Categorized and Annotated Directory of Clojure Libraries*

For more on what the Dining Car is, see [the
README](https://github.com/clojure-dining-car/dining-car/blob/master/README.md).

This directory is manually curated by the Clojure community. Please
endeavor to keep it fresh, consisting of libraries you'd recommend to
friends. `:)`

Herein:

  * Clojure core built-in functions are written without the
    leading "clojure.core/".
  * Standard library names all begin with "clojure.".
  * Contrib libraries are marked "**{contrib}**" and link to Maven
    Central.
  * Third-party libraries link to their canonical Clojars pages.

Library documentation:

  * [the core built-ins and the standard
    library](http://clojure.github.com/clojure/index.html) (see also
    [ClojureDocs](http://clojuredocs.org/))
  * [contrib libraries](http://clojure.github.com/) (Their github
    project pages are linked to from there, as well as from the
    [confluence contrib
    page](http://dev.clojure.org/display/doc/Clojure+Contrib).)

Also very useful are [the cheatsheets with
tooltips](http://jafingerhut.github.com/).

Any links to Java docs point to the ones for version 7:
<http://docs.oracle.com/javase/7/docs/api/>.

Topics here are ordered somewhat haphazardly. Try to put the more
basic ones first.

**********************************************************************

Numbers
=======

  * See the *Numbers* section of the cheatsheet.

  * [math.combinatorics](http://search.maven.org/#search|ga|1|math.combinatorics)
    **{contrib}**: common combinatorial functions

  * [math.numeric-tower](http://search.maven.org/#search|ga|1|math.numeric-tower)
    **{contrib}**: Math functions that deal intelligently with the various types in
    Clojure's numeric tower, as well as math functions commonly found in Scheme
    implementations.


Strings
=======

  * See the *Strings* section of the cheatsheet.

  * clojure.string

  * [useful](https://clojars.org/useful): See useful.string

  * See also the [Java String
    docs](http://docs.oracle.com/javase/7/docs/api/java/lang/String.html).


Data Structures
===============

Sets
----

  * See the *Sets* section of the cheatsheet.

  * clojure.set


Stdin and Stdout
================

  * To read user input from stdin in the repl, use `read-line`.


Process Management
==================

  * clojure.java.shell: Conveniently launch a sub-process providing
    its stdin and collecting its stdout.

  * [conch](https://clojars.org/conch): for shelling out to external programs.
    An alternative to clojure.java.shell.


Files
=====

  * To read the complete contents of a file to a string: `slurp`.

  * To write a string to file: `spit`.

  * clojure.java.io

  * [fs](https://clojars.org/fs): utilities for working with the file
    system.


Date and Time
=============

  * [clj-time](https://clojars.org/clj-time): A date and time library
    for Clojure. Wraps the [Joda
    Time](http://joda-time.sourceforge.net/) library.
  

Testing
=======

  * clojure.test: Easy, quick, standard.

  * [Midje](https://clojars.org/midje): A more featureful test framework.


HTML
====

Creating
--------

  * [hiccup](https://clojars.org/hiccup): Easily generate HTML from
    Clojure data structures.


JSON
====

  * [data.json](http://search.maven.org/#search|ga|1|data.json)
    **{contrib}**: JSON parser/generator to/from Clojure data
    structures.

  * [cheshire](https://clojars.org/cheshire): Clojure JSON and JSON
    SMILE (binary json format) encoding/decoding


Templating
==========

  * [Clostache](https://clojars.org/de.ubercode.clostache/clostache):
    [Mustache](http://mustache.github.com/) for Clojure. Logic-less
    templates.


HTTP
====

Client
------

  * [clj-http](https://clojars.org/clj-http): An idiomatic Clojure
    http client wrapping the apache client.


Web Application Libraries
=========================

  * [ring](https://clojars.org/ring)

  * [compojure](https://clojars.org/compojure): A concise routing library for Ring.

  * [friend](https://clojars.org/com.cemerick/friend): Authentication
    and authorization library for Ring Clojure web apps and services.


Database
========

SQL
---

  * [sqlite-jdbc](http://search.maven.org/#search|ga|1|sqlite-jdbc):
    To use SQLite from Clojure. Requires
    [java.jdbc](http://search.maven.org/#search|ga|1|java.jdbc)
    **{contrib}**. [Example](blob/master/examples/java.jdbc.md).

NoSQL
-----

  * [clutch](https://clojars.org/com.ashafa/clutch): For using [Apache
    CouchDB](http://couchdb.apache.org/)


GUI (Graphical User Interface)
==============================

  * [seesaw](https://clojars.org/seesaw): A Swing wrapper/DSL.
