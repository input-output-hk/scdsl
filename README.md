<p align="center">
  <img width="266" height="185" src="docs/tutorial-v1.3/pix/logo.png">
</p>

# Marlowe

This repository contains Marlowe, a domain-specific language (DSL) for describing financial smart contracts that can be enforced by scripts deployed on a blockchain, as well as some tools for analysing and simulating the execution of contracts written in the DSL.

## Learning about Marlowe and Marlowe Playground

The [Marlowe tutorials](https://alpha.marlowe.iohkdev.io/tutorial/index.html) introduce Marlowe and the Marlowe Playground.

## Versions of Marlowe

The `master` branch contains the latest version of Marlowe, version `3.0`.

An earlier version of Marlowe is described in a [paper](https://iohk.io/research/papers/#2WHKDRA8) that was presented at ISoLA 2018. This version is tagged `v1.3` and a minor update on this is tagged `v1.3.1`.
Versions `1.x`, and `2.0` can also be found in the `master` branch under `semantics-1.0`, and `semantics-2.0`, respectively.

## Build on MacOS


Requirements: Homebrew, Haskell Stack 1.6 or later.

Install Haskell Stack if you haven't already

    $ brew install haskell-stack

    $ brew install glpk
    $ stack setup
    $ stack build

## Build on Ubuntu

    $ sudo apt-get install -y haskell-platform haskell-stack # Install haskell tooks and stack
    $ sudo apt-get install -y glpk-utils libglpk-dev # Install glpk solver
    $ sudo stack upgrade  # Upgrade to the latest version of stack. apt downloads v1.9.3 of stach which cannot fetch lts-15.6 version of ghci. https://github.com/nh2/static-haskell-nix/issues/95
    
    $ stack setup
    $ stack build

## Build Isabelle proofs

Requirements: Isabelle CLI

    $ cd isabelle
    $ isabelle build -d. Test
