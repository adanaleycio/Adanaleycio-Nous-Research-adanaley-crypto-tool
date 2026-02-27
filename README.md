# Feature: Cryptocurrency Price Intelligence Tool

## Overview
This pull request introduces a new tool for the Hermes Agent that allows users to fetch real-time and historical cryptocurrency data via the CoinGecko API.

## Changes
- Created `crypto_price.py` within the tools directory.
- Integrated `price get` and `price history` functionalities.
- Implemented structured JSON output for seamless agent processing.

## How to Test
Run the following command in your terminal:
`python3 hermes_agent/tools/crypto_price.py price get bitcoin --currency usd`

## Technical Details
- **API:** CoinGecko (Public)
- **Dependencies:** `requests`, `argparse`, `json`
