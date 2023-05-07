[![Brittle](https://github.com/keithalbe/brittle/actions/workflows/brittle.yml/badge.svg)](https://github.com/keithalbe/brittle/actions/workflows/brittle.yml)

# Brittle - A Marvel SNAP move analyzer, written in Rust.
> "If something rusty SNAPs, it's Brittle!"

Given a screenshot of the game, Brittle will reveal all possible moves, and provide advanced analytics (e.g. predict the type of deck your opponent is using, chances of winning/losing the current move).

## Brittle works by...
1. `[ in progress ]` Extracting game context from the provided screenshot (i.e. cards on the board, cards in hand, energy, cubes, priority, etc.)
2. `[ to do ]` Iterating through each card in your hand and revealing all possible moves
3. `[ to do ]` Attempting to match the opponents' played cards to a set of known decks or deck-types
4. `[ to do ]` Computing analytics based on aggregated information

## How to use Brittle (Linux)
__Packages:__ `rust`, `cargo`, `opencv-devel`, `clang`

__Compile and Run:__ `cd brittle && cargo run`

## Recommended Development Environment
### OS `Fedora 38`

### Dependency Installation for `Fedora 38`
```
sudo dnf upgrade
sudo dnf install rust cargo opencv-devel clang
```
