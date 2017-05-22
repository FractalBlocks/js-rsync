# js-rsync

Rsync implemented in node over http

## Why?

- It is node.js you can run in multiple platforms, we use that for easy electron integration


# Roadmap

- Make this library transport independent, use HTTP?, use a WebSocket / Node Socket?, Use WebRTC? well this library should expose an stream you can use over the channel you need
- Make this library FileSystem independent. You want to connect with a virtual in-memory FileSystem?, You want to have a FileSystem over indexedDB that replicates using rsync?, well js-rsync can work with it


## Implementation

This is a fork of [ttezel/anchor](https://github.com/ttezel/anchor), thanks to Mihai Tomescu (matomesc@gmail.com) and Tolga Tezel (tolgatezel11@gmail.com) for the initial implementation. We will maintain this repo as we use it in internal projects and share our fixes-refactors as open source code.
