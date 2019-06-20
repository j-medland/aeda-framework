# Asynchronous Event-Driven Actors

Is it possible to build an event-driven asynchronous actor architecture which maintains LabVIEW's strict typing?

- Probably but it will take a lot of tooling to avoid the excessive and sometimes inflexible boilerplate coding.

## Motivation

Lets take two ideas:

1. LabVIEW is a strongly-typed language - if you attempt to connect-up two wires with in-compatible types the VI cannot be run - no debugging required!

2. Event-driven programming is delightful! This is especially true when two asynchronous processes need to communicate without locking.

What if I told you that you could have both of these things and all it would cost you is hours of updating type-defs and writing tons of repetitive code - I am sure you would be thrilled. But assuming that you don't have the time to do all that then I guess it would be nice if there was a framework which was well-tooled to help.

That is ultimately what the AEDA Framework is hoping to achieve.

## Requirements

This code is written in LabVIEW 2018

## Shout-Outs

- [Composed-Systems/Stream Event-Stream Architecture](http://www.labviewcraftsmen.com/blog/actor-systems-with-event-streams)