# The Solidity Contract-Oriented Programming Language

[![Matrix Chat](https://img.shields.io/badge/Matrix%20-chat-brightgreen?style=plastic&logo=matrix)](https://matrix.to/#/#ethereum_solidity:gitter.im)
[![Gitter Chat](https://img.shields.io/badge/Gitter%20-chat-brightgreen?style=plastic&logo=gitter)](https://gitter.im/ethereum/solidity)
[![Solidity Forum](https://img.shields.io/badge/Solidity_Forum%20-discuss-brightgreen?style=plastic&logo=discourse)](https://forum.soliditylang.org/)
[![Twitter Follow](https://img.shields.io/twitter/follow/solidity_lang?style=plastic&logo=twitter)](https://twitter.com/solidity_lang)
[![Mastodon Follow](https://img.shields.io/mastodon/follow/000335908?domain=https%3A%2F%2Ffosstodon.org%2F&logo=mastodon&style=plastic)](https://fosstodon.org/@solidity)

You can talk to us on Gitter and Matrix, tweet at us on Twitter or create a new topic in the Solidity forum. Questions, feedback, and suggestions are welcome!

Solidity is a statically typed, contract-oriented, high-level language for implementing smart contracts on the Ethereum platform.

For a good overview and starting point, please check out the official [Solidity Language Portal](https://soliditylang.org).

## Table of Contents

- [Background](#background)
- [Build and Install](#build-and-install)
- [Example](#example)
- [Documentation](#documentation)
- [Resources](#Resources)
- [Development](#development)
- [Maintainers](#maintainers)
- [License](#license)
- [Security](#security)

## Background

Solidity is a statically-typed curly-braces programming language designed for developing smart contracts
that run on the Ethereum Virtual Machine. Smart contracts are programs that are executed inside a peer-to-peer
network where nobody has special authority over the execution, and thus they allow anyone to implement tokens of value,
ownership, voting, and other kinds of logic.

When deploying contracts, you should use the latest released version of
Solidity. This is because breaking changes, as well as new features and bug fixes, are
introduced regularly. We currently use a 0.x version
number [to indicate this fast pace of change](https://semver.org/#spec-item-4).

## Build and Install

Instructions about how to build and install the Solidity compiler can be
found in the [Solidity documentation](https://docs.soliditylang.org/en/latest/installing-solidity.html#building-from-source).


## Example

A "Hello World" program in Solidity is of even less use than in other languages, but still:

```solidity
// SPDX-License-Identifier: MIT
pragma solidity >=0.6.0 <0.9.0;

contract HelloWorld {
    function helloWorld() external pure returns (string memory) {
        return "Hello, World!";
    }
}
```

To get started with Solidity, you can use [Remix](https://remix.ethereum.org/), which is a
browser-based IDE. Here are some example contracts:

1. [Voting](https://docs.soliditylang.org/en/latest/solidity-by-example.html#voting)
2. [Blind Auction](https://docs.soliditylang.org/en/latest/solidity-by-example.html#blind-auction)
3. [Safe remote purchase](https://docs.soliditylang.org/en/latest/solidity-by-example.html#safe-remote-purchase)
4. [Micropayment Channel](https://docs.soliditylang.org/en/latest/solidity-by-example.html#micropayment-channel)

## Documentation

The Solidity documentation is hosted at [Read the docs](https://docs.soliditylang.org).


## Resources
You will make a faster headway when you start your Solidity journey with the right resources. Apart from the documentation, which is really helpful, these are some other resources that can stregthen your knowledge and aid your understanding:

### Written Tutorials

1. [Solidity by Example](https://solidity-by-example.org/) - It has an actionable project-based learning approach
2. [Tutorialspoint Solidity Tutorial](https://www.tutorialspoint.com/solidity/index.htm) - Tutorialspoint is better for anyone who wants to know the basics of Solidity, especially if you have no programming background.

### Video Tutorials
1. [Smart Contract Programmer](https://www.youtube.com/channel/UCJWh7F3AFyQ_x01VKzr9eyA) - This channel is the official video version of Solidity by Example. If it is the case that you are not understanding a tutorial in Solidity by Example, this channel will always shed more light.

2. [Patrick Collin's Solidity 32-hour Solidity Course](https://youtu.be/gyMwXuJrbJQ) - This 32-hour long tutorial covers the basics of Solidity and its frameworks.

3. [Eat The Blocks](https://www.youtube.com/c/EatTheBlocks) - Eat the Blocks is one of the most popular Solidity channels on YouTube and it has digestible tutorials.


## Development

Solidity is still under development. Contributions are always welcome!
Please follow the
[Developers Guide](https://docs.soliditylang.org/en/latest/contributing.html)
if you want to help.

You can find our current feature and bug priorities for forthcoming
releases in the [projects section](https://github.com/ethereum/solidity/projects).

## Maintainers
* [@axic](https://github.com/axic)
* [@chriseth](https://github.com/chriseth)

## License
Solidity is licensed under [GNU General Public License v3.0](LICENSE.txt).

Some third-party code has its [own licensing terms](cmake/templates/license.h.in).

## Security

The security policy may be [found here](SECURITY.md).
