Welcome to the PureScript wiki! This wiki is meant to be a collaborative effort, so please feel free to add/edit content where it is appropriate to do so.

## Introduction

PureScript is a small strongly, statically typed compile-to-JS language with a number of interesting features, such as:

- Type Inference
- Higher Kinded Polymorphism
- Support for basic Javascript types
- Extensible records
- Extensible effects
- Optimizer rules for generation of efficient Javascript
- Pattern matching
- Simple FFI
- Modules
- Rank N Types
- Do Notation
- Tail-call elimination
- Type Classes

## Libraries

- [Recommended Libraries](https://github.com/purescript/purescript/wiki/Recommended-Libraries)
- [Style Guide](https://github.com/purescript/purescript/wiki/Style-Guide)
- [24 Days of PureScript 2014](https://gist.github.com/paf31/8e9177b20ee920480fbc)

## Tools

- [Editor and tool support](https://github.com/purescript/purescript/wiki/Editor-and-tool-support)
- [Pursuit search engine](http://pursuit.purescript.org)

## Development Environments

- [PureScript and Docker](https://github.com/purescript/purescript/wiki/PureScript-and-Docker)
- [PureScript and NixOS](https://pr06lefs.wordpress.com/2015/01/11/get-started-with-purescript-on-nixos/)

## Articles

- [First Steps With PureScript - Solving Project Euler #1](http://www.purescript.org/learn/getting-started/)
- [The Foreign Function Interface](http://www.purescript.org/learn/ffi/)
- [Handling Native Effects with the Eff Monad](http://www.purescript.org/learn/eff/)
- [FFI Tips](https://github.com/purescript/purescript/wiki/FFI-tips)
- [Test your Javascript with QuickCheck](http://www.purescript.org/learn/quickcheck/)
- [PureScript Without Node](https://github.com/purescript/purescript/wiki/PureScript-Without-Node)

## Talks/Meetups

- [PureScript Presentations](https://github.com/purescript/purescript/wiki/PureScript-Presentations)
- [[PureScript Meetups|Purescript-Meetups]]

## Language Guides

The [PureScript Book](https://leanpub.com/purescript/read) is the recommended approach to learning the language, since it covers more material in greater depth. There is also a language guide, which is more useful as a reference:

- [[Language Guide]]

## Related Languages

- [Related Projects](https://github.com/purescript/purescript/wiki/Related-Projects)
- [Differences from Haskell](https://github.com/purescript/purescript/wiki/Differences-from-Haskell)
- [Alternate compiler backends](https://github.com/purescript/purescript/wiki/Alternate-backends) for various target languages

## TL;DR
* [Install PureScript](http://www.purescript.org/download/)
* [Install Node.js](https://nodejs.org/): `brew install node`/`pacman -S nodejs`/`choco install nodejs`/[Download Node.js](https://nodejs.org/)
* [Install Pulp](https://github.com/bodil/pulp): `npm install -g pulp bower`
* GO: `pulp init`, `pulp dep install purescript-tuples`, `pulp build --to output.js`, etc.