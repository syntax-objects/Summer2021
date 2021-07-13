# Syntax Parse Bee 2021

Hi folks,

**Write a macro with Racket this summer! Win stickers!**

The purpose of this event is to grow the [syntax-parse-example](https://docs.racket-lang.org/syntax-parse-example/index.html) [documentation](https://docs.racket-lang.org/syntax-parse-example/index.html) and [repository](https://github.com/bennn/syntax-parse-example) to grow as a resource for the Racket community. (You can also contribute directly to the [syntax parse examples repository](https://github.com/bennn/syntax-parse-example))

_It's like a Quilting Bee, but for syntax parse macros!_

As we hope to include many new examples derived from the entries in the syntax-parse-example [documentation](https://docs.racket-lang.org/syntax-parse-example/index.html) and [repository](https://github.com/bennn/syntax-parse-example) we ask entrants to licence their code under the same MIT license [1] as used by Racket, and your text under the http://creativecommons.org/licenses/by/4.0/ license.

Ground Rules:
* you can write any macro as long as it uses [syntax-parse](https://docs.racket-lang.org/syntax/stxparse.html) somehow
* enter as many times as you like
* the first 20 individuals who enter will win exclusive stickers
* open July 1 to September 1

Submit by opening an issue here: [submit your entry](https://github.com/syntax-objects/Summer2021/issues/new?assignees=&labels=entry&template=enter-the-syntax-parse-bee.md&title=%5Bentry+-+name%2Fdescription+of+macro%5D)

To help you get started, we suggest two categories of before-and-after macro:

1. Code Cleaning : Introduce a macro where there was none before. Look for ways
   to make your source code more beautiful and/or less repetitive.

2. Macro Engineering : Use the tools in syntax-parse to improve an existing
   macro (which may or may not currently use syntax-parse). Try to make the old
   macro more maintainable, more robust against errors, and/or more flexible.

Updates will be via Racket News, Racket-Users, Slack, Discord & Reddit.

Whatever you decide, we hope that you learn and have fun!

- Ben + Stephen


PS a 'Bee' is a community effort toward a common goal. A quilting bee is for
making a quilt. In this case the quilt is a patchwork of syntax-parse macros.


- - -

## Resources/notes

Q. Why `syntax/parse` macros?  A. `syntax/parse` provides functionality for writing macros and specifying syntax that automatically validates macro uses and reports syntax errors.

Q. I've not written macros before how can I get started?

A. The following resources are recommended, but if you run into trouble don't hesitate to ask for help on [racket-users](https://lists.racket-lang.org/), [Slack](https://racket-slack.herokuapp.com/), [Discord](https://discord.gg/6Zq8sH5) or [#racket IRC](https://kiwiirc.com/nextclient/irc.libera.chat/#racket).

The [Fear of Macros tutorial](https://www.greghendershott.com/fear-of-macros/) is a great resource for basic macro engineering (though, not syntax-parse in particular).

The Racket Guide also provides an introduction to macros, but like Fear of Macros doesn't cover Syntax Parse: 
 https://docs.racket-lang.org/guide/macros.html

Mythical Macros tutorial:
 https://soegaard.github.io/mythical-macros/

Macros and Languages in Racket book draft:
 http://rmculpepper.github.io/malr/

Syntax parse docs:
 https://docs.racket-lang.org/syntax/stxparse.html

Syntax parse examples:
 https://docs.racket-lang.org/syntax-parse-example/

Extra syntax classes:
 https://docs.racket-lang.org/syntax-classes/

Racket includes a macro debugger to make it easier for experienced programmers to debug their macros and for novices to study their behavior.
 https://docs.racket-lang.org/macro-debugger/index.html

Fine print:
* this is an UNOFFICIAL event run by Racket users (@spdegabrielle and @bennn)
* entries must be submitted under the [MIT license [1]](https://github.com/racket/racket/blob/master/racket/src/LICENSE-MIT.txt) for code, and [http://creativecommons.org/licenses/by/4.0/](http://creativecommons.org/licenses/by/4.0/) [3] license for the included text.
* stickers will be mailed via USPS; international entries are allowed
* please abide by the [Racket Friendly Environment Policy [2]](https://racket-lang.org/friendly.html)


[1] https://github.com/racket/racket/blob/master/racket/src/LICENSE-MIT.txt

[2] https://racket-lang.org/friendly.html

[3] http://creativecommons.org/licenses/by/4.0/

