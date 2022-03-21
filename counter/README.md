NOTE - If you are using windows you need WSL to run rust build commands.  
### Environment Setup
1. Install Rust from https://rustup.rs/
2. Install Solana from https://docs.solana.com/cli/install-solana-cli-tools#use-solanas-install-tool

### Build and test for program compiled natively
```
$ cargo build
$ cargo test
```

### Build and test the program compiled for BPF
```
$ cargo build-bpf
$ cargo test-bpf
```
This is the transaction that we make to the contract deployed as an Account.
![solana](https://user-images.githubusercontent.com/78919021/159208682-5c27814b-690c-4a91-b348-54315aa94c59.png)

This is the Account that processes the transactions! 
![account](https://user-images.githubusercontent.com/78919021/159208716-57b1ead2-6f1c-4374-b2c5-d143610547ee.png)
