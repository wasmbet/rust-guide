# rust-guide

```sh
curl https://sh.rustup.rs -sSf | sh
export PATH=$HOME/.cargo/bin:$PATH
rustup default stable
cargo version

rustup update stable
rustup target list --installed
rustup target add wasm32-unknown-unknown
rustup default stable
```

# secretcli-guide

```sh
wget https://github.com/chainofsecrets/SecretNetwork/releases/download/v1.0.0/secretcli-linux-amd64
./secretcli config node tcp://bootstrap.secrettestnet.io:26657
```
