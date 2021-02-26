# Coup Simulator CLI

A cli for simulating a game of Coup! I really love this game, and want to write an AI for it. I've been learning rust, and thought this would be a good project to mess around with.

## Usage

```
# View that sweet structopt help message
cargo run -- --help

# Launch yourself a game of coup against an easy cpu
cargo run -- --dumb-cpus Chandler
```

### TODO List
- Create a smarter enemy player
- Make interactive mode a first class concept
- Stepwise Portion. Game waits for updates, but can still see statusw
- Make Player configuration some sweet sweet Structopt
- Implement Ambassador
