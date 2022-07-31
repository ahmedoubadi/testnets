# Evmos Testnet

## Instructions

## Full nodes and general participants

Follow the instructions on the official documentation to [join the testnet](https://kynno.dev/validators/testnet.html) and how to obtain tokens using the [faucet](https://kynno.dev/developers/faucet.html).

## Genesis File

Download the zipped genesis file [genesis.zip](./genesis.zip)

Extract it with command

```bash
unzip genesis.zip
```

Verify the SHA256 checksum using:

```bash
sha256sum genesis.json
# 5d0cecf3e6abccbff5baa74bcb7b457e1a3fd3ffb81f65f1889b9bd0cac98f28  genesis.json
```

## Details

- Network Chain ID: `kynno_9700-1`
- EIP155 Chain ID: `9700`
- `kynnod` version: [`v1.0.0`](https://github.com/ahmedoubadi/core/releases)
- Faucet: [faucet.kynno.dev](https://faucet.kynno.dev)
- EVM explorer: [evm.kynno.dev](https://evm.kynno.dev)

## Seeds & Peers

You can find seeds & peers on the seeds.txt and peers.txt files, respectively. If you want to share your seed or peer, please fork this repo and and add it to the bottom of the corresponding .txt file.
