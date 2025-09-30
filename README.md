# eth-balance-checker

A Python CLI tool to fetch Ethereum wallet balances (ETH + ERC-20 tokens) using Web3.  
Works with any public Ethereum RPC endpoint (e.g. Infura, Alchemy).

## Features
- Query ETH balance for one or multiple Ethereum addresses.
- Query ERC-20 token balances given contract addresses.
- Output in table format.
- Works with free public RPC endpoints (no paid API required).

## Requirements
- Python 3.9+
- Dependencies listed in `requirements.txt`
- An Ethereum RPC URL (free from [Infura](https://infura.io/), [Alchemy](https://www.alchemy.com/), or [Cloudflare RPC](https://cloudflare-eth.com))

## Installation
```bash
python3 -m venv .venv
source .venv/bin/activate      # macOS/Linux
# .venv\Scripts\Activate.ps1   # Windows PowerShell

pip install -r requirements.txt
