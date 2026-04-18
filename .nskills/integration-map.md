# Integration Map

How components connect and what data flows between them.

### Erc721-stylus --> Frontend-scaffold

- **Source**: Erc721-stylus (`83cd222f`)
  - Output ports: NFT Contract (contract)
- **Target**: Frontend-scaffold (`86911802`)
  - Input ports: Contract ABI (contract), Network Config (config)

### Frontend-scaffold --> Wallet-auth

- **Source**: Frontend-scaffold (`86911802`)
  - Output ports: App Context (config)
- **Target**: Wallet-auth (`dcdeca29`)
  
