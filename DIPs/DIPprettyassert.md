# Custom assert diagnostics

| Field           | Value                                                           |
|-----------------|-----------------------------------------------------------------|
| DIP:            | (number/id)                                                     |
| Review Count:   | 0                                                               |
| Author:         | Per Nordlöw, Sebastian Wilzbach (seb [at] wilzba [dot] ch       |
| Implementation: | (links to implementation PR if any)                             |
| Status:         | Will be set by the DIP manager (e.g. "Approved" or "Rejected")  |

## Abstract

Provides custom assert diagnostics.
Allow for assert to do pretty printing of its failing expression when flagged for in call to compiler. Printing is configurable via specific sets of (template) function overloads.

### Links

Optional sections containing links to existing discussions, research papers or any
other supplementary materials.

- [Original DIP83](https://wiki.dlang.org/DIP83)
- [Improving assert-printing in DMD NG thread from 2015](https://forum.dlang.org/post/holdxspayjguauomrbcx@forum.dlang.org)
- [Original DMD PR](https://github.com/dlang/dmd/pull/263)
- [Issue 5547 - Improve assert to give information on values given to it when it fails](https://issues.dlang.org/show_bug.cgi?id=5547#c3)
- [assertPred - druntime PR](https://github.com/dlang/druntime/pull/41)

## Rationale

State a short motivation about the importance and benefits of the proposed
change.  An existing, well-known issue or a use case for an existing projects
can greatly increase the chances of the DIP being understood and carefully
evaluated.

## Description

Detailed technical description of the new semantics.
Language grammar changes (per https://dlang.org/spec/grammar.html)
needed to support the new syntax (or change) must be mentioned.

No grammar changes are required, but new overloads to D runtime are necessary.

### Breaking changes / deprecation process

Provide a detailed analysis on how the proposed changes may affect existing
user code and a step-by-step explanation of the deprecation process which is
supposed to handle breakage in a non-intrusive manner. Changes that may break
user code and have no well-defined deprecation process have a minimal chance of
being approved.

### Examples

A more practical explanation of DIP semantics should be given by showing
several examples of its idiomatic application. Inspecting vivid code examples
is usually an easier & quicker way to evaluate the value of a proposal than
trying to reason about its abstract description.

## Copyright & License

Copyright (c) 2018 by the D Language Foundation

Licensed under [Creative Commons Zero 1.0](https://creativecommons.org/publicdomain/zero/1.0/legalcode.txt)

## Review

Will contain comments / requests from language authors once review is complete,
filled out by the DIP manager - can be both inline and linking to external
document.
