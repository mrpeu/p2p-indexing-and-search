# Intro to P2P Indexing and Search
Welcome to our [NodeConf Remote 2020](https://www.nodeconfremote.com/) workshop on P2P indexing and search! 

Over the course of this workshop, we'll be learning the ins-and-outs of designing and sharing P2P-friendly data structures, ultimately building up to [Hyperbee](https://github.com/mafintosh/hyperbee), a P2P database that supports "sparse querying", where peers reading from the database only download the portions of the database they use, on-demand. 

We'll put Hyperbee through its paces, first exploring large, real-world datasets, then extending the database to make custom queries fast.

Throughout these exercises, we'll be using the [Hypercore Protocol](https://hypercore-protocol.org), a collection of modules for building and sharing P2P data structures. Each exercise builds on the previous, but feel free to jump around according to your familiarity with the concepts!

## Getting Started
Everyone should first read [Problem 0](problems/00.md) as an orientation, then do [Problem 1](problems/01.md), to make sure things are set up correctly.

## Not familiar with Hypercore?
[Problems 2-3](problems/02.md) give a bit of background, and will introduce you to the basics of creating append-only logs (Hypercores) and sharing them with peers.

## Want to build data structures using Hypercores?
If you've already worked with Hypercore, but want to learn about designing append-only data structures on top of it, using embedded indexes, go ahead and jump to [Problem 4](problems/04.md).

## Just want to play with Hyperbee?
If you know how append-only data structures work, and you just want to play around with Hyperbee, head over to [Problem 7](problem/07.md).

## Chat with us
Come join our [Discord](https://chat.hypercore-protocol.org) to ask questions!

### License
MIT
