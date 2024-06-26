# Ore CLI 

A command line interface for the Ore program.

fork from [HardhatChad/ore-cli](HardhatChad/ore-cli)

## Building

To build the Ore CLI, you will need to have the Rust programming language installed. You can install Rust by following the instructions on the [Rust website](https://www.rust-lang.org/tools/install).

Once you have Rust installed, you can build the Ore CLI by running the following command:

```sh
cargo build --release
```

## Windows

```
.\target\release\ore.exe ^
    --send-rpc <Send RPC URL> ^
	--rpc <Query RPC URL> ^
    --keypair <Private Key.json> ^
    --priority-fee 1 ^
    mine ^
    --threads 16
```