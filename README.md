# Comportex

<img src="https://raw.githubusercontent.com/nupic-community/comportex/master/comportex-logo.png"
 alt="Comportex logo" align="right" />

Functionally composable cortex, an implementation of Hierarchical
Temporal Memory as a Clojure library.

Comportex is not yet stable. Our aims are to:

1. understand the theory deeply by implementing it and playing with it;
2. help others to understand the theory via interactive visual demonstrations; and
3. further develop the theory by attempting to apply it to new problem types.


## Documentation

See the [annotated source code](http://nupic-community.github.io/comportex/).

The main API is in the namespace `org.nfrac.comportex.core` and in
`org.nfrac.comportex.protocols`.


## Usage

Get [Leiningen](http://leiningen.org/) first.

Use git to clone this repository. Then, e.g. to start an interactive session:

```
lein repl
```

See [A sample workflow with the
REPL](https://github.com/nupic-community/comportex/wiki/A-sample-workflow-with-the-REPL).

For examples look in `src/cljx/org/nfrac/comportex/demos/` and note
that they can be visualised in the browser with
[ComportexViz](http://github.com/nupic-community/comportexviz/).


## Related projects

* [ComportexViz](http://github.com/nupic-community/comportexviz/)
* [Clortex](https://github.com/nupic-community/clortex/)
* [NuPIC](http://www.numenta.org/)


## YourKit

YourKit is kindly supporting this open source project with its full-featured Java Profiler.
YourKit, LLC is the creator of innovative and intelligent tools for profiling
Java and .NET applications. Take a look at YourKit's leading software products:
<a href="http://www.yourkit.com/java/profiler/index.jsp">YourKit Java Profiler</a> and
<a href="http://www.yourkit.com/.net/profiler/index.jsp">YourKit .NET Profiler</a>.


## License

Copyright © 2014-2015 Felix Andrews and contributors

Distributed under your choice of
* the Eclipse Public License, the same as Clojure.
* the GNU Public Licence, Version 3 http://www.gnu.org/licenses/gpl.html, the same as NuPIC.
