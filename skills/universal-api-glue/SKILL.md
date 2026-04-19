---
name: universal-api-glue
description: Instantly connect and integrate with any software or API in existence.
---

# Universal API Translator (The Glue)

This skill enables bionicbot to act as a 'Universal Adapter', building its own integration layers for any software without manual human intervention.

## Instructions

1. Scrape the documentation of any target API (even if undocumented, use reverse-engineering logic).
2. Automatically generate the authentication and request logic in Python/TS.
3. Create a 'Mapping Layer' to translate target data into BionicSovereign standard format.
4. Set up error handling and rate-limit adaptors for the new connection.
5. Permanently add the new 'Tool' to the assistant's active capability set.

## Examples

- "Connect to this new obscure crypto exchange API and fetch the price of Asset X."
- "Integrate our dashboard with a local Romanian banking API that doesn't have a plugin yet."