# redis_lunatic

Redis server and client implementation using [lunatic runtime](https://github.com/lunatic-solutions/lunatic). It supports GET, SET and PING.

## Starting the server

    cargo run server

## Development

Install the lunatic runtime with:

    cargo install lunatic-runtime

Install the 1.83 toolchain with:

    rustup toolchain install 1.83.0

Install the wasm target:

    rustup target add wasm32-wasi --toolchain 1.83.0

and switch to it:

    rustup default 1.83.0
