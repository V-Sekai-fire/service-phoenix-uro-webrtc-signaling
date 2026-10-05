# service-phoenix-uro-webrtc-signaling

An Elixir web service that relays WebRTC offers, answers and candidates between the peers in a lobby.

## What it is for

A client joins or creates a lobby over a websocket channel, learns its own peer id and when other
peers arrive or leave, and exchanges session offers, answers and candidates with them through the
server until the lobby's creator seals it. The lobby channel's module documentation states the
protocol.

## Build and run

```sh
mix setup
mix phx.server
```

## Licence

This repository does not state a licence.
