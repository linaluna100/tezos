# Octez node on Akash
[Tezos](https://tezos.com/) is an open-source platform that addresses key barriers facing blockchain adoption for assets and applications backed by a global community of validators.

## Deploy on Akash
Open [Akash Console](https://console.akash.network/) website and use deploy.yaml file as template.

## Flags
You can change the --network and --history-mode in the deploy.yaml file.

--network:
- mainnet (this is the default)
- sandbox
- ghostnet

--history-mode:
- full
- rolling
- archive

## Interaction
Example interactions with node:
- `http://node:8732/chains/main/blocks/head/header` - Get the most recently finalized block header
- `http://node:8732/chains/main/is_bootstrapped` - The bootstrap status of a chain
- `http://node:8732/version` - Get information on the node version

Replace `http://node:8732/` with URI from your deployment.

---
[OpenTezos Documentation](https://opentezos.com/node-baking/deploy-a-node/installation/)
[Shell RPCs](https://tezos.gitlab.io/shell/rpc.html)
