# dts_py_transform
Convert Typescript definition files into Python equivalents (PEP-484)

# Status
For now I've implemented this as a basic pushdown automata/state machine, and it's working for my needs. That said, a cleaner and more reliable approach is to rely on Typescript's AST/compiler API. I may add that in the future if I end up finding problems with the existing approach.

# Future Goals
* Eventually I would like to create a repo which automatically converts all Definitely Typed type annotations into their Python equivalents.

* Create an easy way to have interop between Python and Javascript, along with (optionally) webkit browser instances. I far prefer Python to JS/TS, but the ecosystem around Javascript is pretty excellent... I'd love to be able to use Python for my code logic and rely on TS + React for my front end. I'd like to accomplish that without having to rely on a transpiler.
