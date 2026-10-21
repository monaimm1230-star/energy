# E-Drive Backend

Flask backend for **E-Drive**, a peer-to-peer energy-trading platform where users can buy and sell energy directly from each other.

## Features

- **User accounts:** Email signup and Google Sign-In
- **Buyer and seller listings:** Post energy offers and browse available ones
- **AI bidding engine:** Ranks offers by a weighted score of price (35%), quantity (35%), distance (20%) and other factors (10%)
- **Trade confirmation:** Buyer and seller confirm a deal, with automatic retries for reliability
- **Blockchain-backed records:** Confirmed trades are recorded on a custom hybrid blockchain
- **Automatic wallets:** A blockchain wallet is created for both parties when needed
- **Multi-currency support:** PKR, USD and EUR, with configurable exchange rates
- **Unit preferences:** Show energy as units or kWh

## Blockchain Highlights

- ARM-256 hashing
- AES-GCM encryption
- Dual PoW / PoA chains
- Merkle trees
- ECDSA wallets

## Tech Stack

- Python, Flask
- MongoDB Atlas
- Render (hosting)



## Team

Aqib Masood, Monaim Ibrahim. Supervisor: Engr. Hussain Asif.
