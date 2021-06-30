
# Learning about Marlowe and the Marlowe Playground

Marlowe is a domain-specific language (DSL) for writing financial contracts that run on blockchain. 

The best place to go to learn about Marlowe and to try it out is the [Marlowe Playground](https://alpha.marlowe.iohkdev.io/), which also contains a [tutorial](https://alpha.marlowe.iohkdev.io/doc/marlowe/tutorials/index.html) about Marlowe.

## Earlier versions of Marlowe

This document describes the different materials available for learning about Marlowe and the online tool that accompanies it: the Marlowe Playground. originally called Meadow. It also advises you where to begin, depending on what you want to learn, and where you are starting from.

Marlowe is realised as DSL embedded in Haskell, but it is possible to use Marlowe without being a Haskell expert. Marlowe is a live project, and the materials here describe two versions of Marlowe: the earlier [version 1.3]( https://github.com/input-output-hk/marlowe/tree/v1.3), and the [current version](https://github.com/input-output-hk/marlowe/tree/master/semantics-2.0), 2.0.

The Marlowe Playground is also available in two versions:

* It was originally called [Meadow](https://input-output-hk.github.io/marlowe/) supports v1.3, and this version supports contract development using Blockly, a visual programming environment. It also supports the development of “embedded” contracts using aspects of Haskell, but because this runs a Haskell environment in the browser, it has a substantial latency.

* The latest version, the [Marlowe Playground](https://prod.meadow.marlowe.iohkdev.io), supports development of embedded contracts is a much more efficient way, as well as presenting a substantially cleaner interface, but doesn't currently support visual program development.

## Where should I start?

I want to learn the ideas behind Marlowe, but not to write Marlowe contracts myself.

* The first parts of the [tutorial](./tutorial-v1.3/README.md) and the [Udemy course](https://www.udemy.com/marlowe-programming-language/) will give you this introduction.

I want to learn how to write simple Marlowe contracts, and to run them in the Meadow tool.

* The [Udemy course](https://www.udemy.com/marlowe-programming-language/)  and [tutorial](./tutorial-v1.3/README.md) will give you an introduction to building contracts using Blockly.
* If you are not a Haskell programmer, then you can skip the tutorial sections on [Understanding the semantics](./tutorial-v1.3/marlowe-semantics.md) and [Using Marlowe](./tutorial-v1.3/using-marlowe.md).

I have learned about Marlowe 1.3, and written contracts there, but I want to convert to v2.0 and use the Marlowe Playground.

* You can find out about the [differences between v1.3 and v2.0](./tutorial-v1.3/differences.md), and [this checklist](./tutorial-v1.3/checklist.md) will help you to convert contracts from v1.3 to v2.0.

I am a Haskell programmer, and I want to get started developing Marlowe contracts embedded in Haskell and to run them in Haskell and the Marlowe Playground.

* To do this, follow the [tutorial](./tutorial-v2.0/README.md) on the current version of Marlowe and develop your programs in the [Marlowe Playground](https://prod.meadow.marlowe.iohkdev.io).

## Miami Hackathon

The [challenge](./challenge.md) for the Hackathon at the Miami summit.

The [Marlowe slides](./SummitMarlowe.pdf) (PDF) from the hackathon.

## Materials available

This section lists all the learning resources for Marlowe, the Marlowe Playground and Meadow.

* [Tutorial](./tutorial-v1.3/README.md) for version 1.3 of Marlowe and the first version of the Meadow tool.
* [Tutorial](./tutorial-v2.0/README.md) for version 2.0 of Marlowe and the Marlowe Playground.
* An [overview](./tutorial-v1.3/differences.md) of the differences between v1.3 and v2.0.
* A [checklist](./tutorial-v1.3/checklist.md) for converting a v1.3 contract to v2.0.
* [Udemy course](https://www.udemy.com/marlowe-programming-language/) on Marlowe (v1.3) and Meadow.
* [Paper](https://iohk.io/research/papers/#2WHKDRA8) on Marlowe, describing v1.3 and  Meadow.
* [Video](https://youtu.be/_loz70XkHM8) run-through of the original Meadow.

