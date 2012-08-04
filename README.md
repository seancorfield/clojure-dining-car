**Clojure Dining Car**

*A Categorized and Annotated Directory of Clojure Libraries*

It's purpose is to help answer these 2 questions:

 1. "What library should I use to do $x?", and then
 2. "What needs to go in my project.clj to use this library?"

The Dining Car is one big document. View it
[here](https://github.com/uvtc/clojure-dining-car/blob/master/dining-car.md).

It's categorized and task-oriented, and contains short descriptions of
the libraries, possibly including mention of what they're most useful
for. Sometimes with links to example usage. It's not
comprehensive. It's necessarily just a bit opinionated, but we all
agree to be nice, so that shouldn't be a problem. `:)`

It's a *community-driven* resource, and editing is *easy* (like a
wiki). Please contribute. Just log in to github, go to [the dining
car](https://github.com/uvtc/clojure-dining-car/blob/master/dining-car.md),
and click the "Edit" button at the top right of the content
area. Github will automatically take care of version control details
(forking & branching) and let you click a button to submit your
changes.


Editing Tips
------------

Items in the Dining Car should start off with a link to the project's
Clojars page (or to Maven Central if it's a contrib library or
otherwise not available from Clojars), followed by a brief description
of the library. Though, there's no link if the library is one of the
[standard libraries](http://clojure.github.com/clojure/index.html).

(Any links to Maven Central should be formed such that they contain
the project name and lead right to it, for example:
`http://search.maven.org/#search|ga|1|the.project.name`.)

It may be useful to provide links to example usage of contrib and
third-party libraries. Examples involving [core built-ins and/or the
standard library](http://clojure.github.com/clojure/) belong at
[ClojureDocs](http://clojuredocs.org/) and don't need to be linked
to. Examples involving [contrib](http://clojure.github.com/) can for
now go into [the Dining Car's examples
directory](https://github.com/uvtc/clojure-dining-car/tree/master/examples)
until such time as an updated ClojureDocs can adopt them. (Note you
*might* also find contrib examples at their individual github project
pages (linked to from the docs at clojure.github.com and also from the
[confluence contrib
page](http://dev.clojure.org/display/doc/Clojure+Contrib))).


FAQ
---

  * **"This duplicates
    [Clojure-Toolbox](http://www.clojure-toolbox.com/). Why not use
    that instead?"**

    My understanding is that the author of the toolbox has plans to
    make it more sophisticated. The Dining Car takes the opposite
    approach (it's just a .md file). Also, the DC includes short
    descriptions and provides links to Clojars pages (rather than
    github project pages).

  * **"Why does the Dining Car provide links to Clojars pages rather
    than github project pages?"**

    Because the first thing a user needs to know after selecting a
    library is what should go into their project.clj file in order to
    use the library. And the Clojars page for a given project shows
    that information.

    Also, a given project's canonical Clojars page should have the
    link to its corresponding github project page. So there's no need
    to duplicate that information in Plaid.

  * **"I can search clojars.org myself. Why do I need a link from
    the Dining Car?"**

    Because it can sometimes be difficult to locate the *canonical*
    Clojars page for a given project. (There may be multiple
    like-named clojars pages for a given project.)

  * **"Why not use
    [ClojureSphere](http://clojuresphere.herokuapp.com/) to locate
    libraries?"**

    ClojureSphere provides lots of useful information.

    The Dining Car is more rustic and is easily editable. If you think
    library $L1 is good for task $T, and works well with another
    library $L2, but $L3 is also an alternative worth considering, say
    so in the brief comments for that library.

  * **"What if a given Clojars page doesn't provide a link to its
    github project page?"**

    If you find such a Clojars page, ask around to locate the
    corresponding github project page and then either file a bug
    report or else edit the project's project.clj yourself adding a
    :url key that contains the github project url.

  * **"What Clojure implementations is the Dining Car for?"**

    Currently, only Clojure-JVM. Perhaps in the future it will expand
    to serve other implementations.

  * **"Should I list pure Java libraries in the Dining Car?"**

    If they're available via [Maven
    Central](http://search.maven.org/), and if there's no pure Clojure
    alternative, go ahead. The Dining Car is intended to be useful for
    finding what you need to get your Clojure projects done.

\#\#\#

John Gabriele, 2012
