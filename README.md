# 🌙 Onchain GN (Celo Mainnet)

Un contrat minimaliste pour dire "GN" directement on-chain sur [Celo](https://celo.org).

## 🚀 Détails du contrat

- **Nom :** OnchainGN  
- **Réseau :** Celo Mainnet  
- **Adresse :** [`0xFaFA48Ed2102A663223d2b0E35Bd5cDCaeD8Bd67`](https://celoscan.io/address/0xFaFA48Ed2102A663223d2b0E35Bd5cDCaeD8Bd67)  
- **Licence :** MIT  
- **Compilateur :** Solidity v0.8.24+commit.e11b9ed9  

## 🧠 Description

Ce contrat permet à n’importe qui de publier un message “GN” on-chain.  
Chaque message est stocké et émet un événement `NewGN` avec :
- l’adresse de l’auteur  
- le timestamp  
- le message

### 📜 Fonction principale

```solidity
function postGN(string calldata message) external
