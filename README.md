# dts_py_transform
Convert Typescript definition files into Python 3 (compliant with PEP-484)

# Status
For now I've implemented this as a basic pushdown automata/state machine, and it's working for my needs. That said, a cleaner and more reliable approach is to rely on Typescript's AST/compiler API. I may add that in the future if I end up finding problems with the PDA approach.

# Future Goals
* Create a repo which automatically converts all Definitely Typed type annotations into their Python 3 equivalents, along with an easy tool for installing said definitions.

* Create an easy way to have interop between Python and Javascript, along with built-in support for GTK Webkit. I far prefer Python to JS/TS, but the ecosystem around Javascript is pretty impressive... I'd love to be able to use Python for my core logic and rely on TS + React for my front end. I don't want to rely on a transpiler (whether ahead of time or at run time) to accomplish this as it tends to slow my workflow down significantly.
