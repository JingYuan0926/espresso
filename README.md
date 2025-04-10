# Caffeinated and Code

## Core Rollup Requirements - Rollup Liveness Verification

This repository contains the implementation and verification details for our Arbitrum rollup deployment.

### Rollup 1

| Detail | Value |
|--------|-------|
| CreateRollup Transaction Hash | [0xce1d0dc0399c7b8233f0946612c0bbf036eb9125ec49b0a015d174a2f6733d76](https://sepolia.arbiscan.io/tx/0xce1d0dc0399c7b8233f0946612c0bbf036eb9125ec49b0a015d174a2f6733d76) |
| IP Address of Cloud Server | 157.230.195.21:8547 |
| RPC URL | http://157.230.195.21:8547/ |
| Chain ID / Namespace | 888888 |

### Verification

- [Video Demonstration](https://drive.google.com/drive/folders/1er97FC8JzYJagWpRoKyscwBv5wgQbOTg)

### Test Commands

You can verify the rollup's functionality using the following `cast` commands:

```bash
# Send a transaction to a receiver address
cast send '<receiver address>' --value 1 --private-key '<sender private key>' --rpc-url http://157.230.195.21:8547/

# Check balance of a wallet address
cast balance '<wallet address>' --rpc-url http://157.230.195.21:8547/

# Check the current block number
cast block-number --rpc-url http://157.230.195.21:8547/
```
