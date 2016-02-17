# Elm TODO

This is a list of things that we could do to improve the Elm programming language ecosystem.
The list started when I noticed a few things mentioned on [Elm #general Slack channgel](https://elmlang.slack.com/messages/general/).


Tooling
-------

* Tool to determine the type signature for a function
    * Work-around: Give it a bad signature, read the compiler error
        * Might need to use the `--warn` option
        * Probably have to 
* Tool to find unused functions, types, and imports


Compiler
--------

* Self-hosting (port the compiler to Elm)
    * This is likely *very* long term
* Different targets:
    * LLVM
    * Erlang VM (BEAM)
