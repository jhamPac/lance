[![Build Status](https://travis-ci.org/OpherV/Incheon.svg?branch=master)](https://travis-ci.org/OpherV/Incheon) [![Inline docs](http://inch-ci.org/github/opherv/incheon.svg?branch=develop)](http://inch-ci.org/github/opherv/incheon)
[![Slack](http://incheongg-slack.herokuapp.com/badge.svg)](http://incheongg-slack.herokuapp.com)

<img src="https://cloud.githubusercontent.com/assets/3951311/21020499/6f125344-bd7d-11e6-86e4-a4bb16b32f2a.png" style="width: 100%" alt="Lance logo">

# [Lance](http://lance.gg) is a real-time multiplayer game server

It provides an extendible Node.JS based server, on which game logic runs, as well as a client-side library
which synchronizes the client's game state with the server game state.  In order
to provide a smooth visual experience for each connected client, Lance implements
efficient networking methods, position interpolation and extrapolation, user input
coordination, shadow objects, physics and pseudo-physical movement, automatic
handling of network spikes.

Lance aims to optimize the player's visual experience, while providing
a simple development model which is highly configurable and easy to analyze
and debug.

## See it in action
Check out the official demo: [Spaaace](http://spaaace.herokuapp.com)

## Features:

* Focus on writing your game. Lance takes care of the netcode
* Can support any type of game or genre  
* Optimized networking
    * TCP via websockets
    * Communication is packed and serialized into binary
    * Automatic handling of network spikes with step correction
* Intelligent sync strategies for lag handling
    * Extrapolation (client side prediction) with step re-enactment or:
    * Interpolation for optimal object motion
* Tools for debugging and tracing

More features in the pipeline:

* UDP via WebRTC
* Full-stack testing suite
* Replay saving
* More physics engines

## That's so neat! Where do I start?

The official [Lance documentation](http://docs.lance.gg) contains articles on theory and rational, as well as the structure and architecture of the project.

If you feel like learning by doing you can start with first tutorial, [My first game: Pong](http://docs.lance.gg/develop/tutorial-MyFirstGame.html) which contains step-by-step on implementation of a networked version of this classic game.

## Something went wrong! I need help!

If you're not exactly sure how to do something, [Stack Overflow](http://stackoverflow.com/questions/tagged/incheon) is your friend.

If you've encountered a bug and it's not already in the [issues page](https://github.com/lance-gg/lance/issues), open a new issue.

## I'd like to join in

For discussing Lance, multiplayer games or just hanging out you're invited to join us on [slack](http://slack.lance.gg).

## Built something cool with Lance?

Please [Let us know](http://www.twitter.com/opherv)! We'd love to play it, and feature it on the [Lance homepage](http://lance.gg).
