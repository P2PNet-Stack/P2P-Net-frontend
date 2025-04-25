# P2P-Net  
### A decentralised peer to peer exchange for easy convesion between fiat and cryptocurrency on starknet

#### P2P-Net is a decentralized peer-to-peer platform built on Starknet, designed to simplify and secure the conversion of cryptocurrency to fiat and vice versa. By leveraging Starknet's scalability and low fees, p2p-net empowers users to execute fast, trustless, and efficient transactions without the need for intermediaries.

## Why P2P-Net?
Converting fiat to stark-based cryptocurrencies and vice versa can be a hassle due to delays and certain restrictions in centralised exchanges and so on. With P2P-Net, we're breaking that barrier and making it easy and fast to switch between cash and cryptocurrency. You don't have to use a centralised exchange to get stark or any other token on starknet



## How It Works

1. **Ad Creation & Approval:**
   - **Sell Ad:**  
     A merchant creates a sell ad by entering the token amount and price. They then approve the exact token amount for the contract.
   - **Buy Ad:**  
     A merchant creates a buy ad by specifying the desired token amount and price, and approves the required payment funds.

2. **Partial Transactions:**
   - Buyers or sellers can fulfill any portion of an active ad. The contract updates the remaining amount in real time, so ads can be partially filled until the full amount is reached.

3. **Secure Token & Payment Handling:**
   - The contract uses safe transfer methods and reentrancy guards to securely lock and transfer tokens, ensuring funds are only moved when all conditions are met.
   - If any issues occur, the system handles errors gracefully and notifies the user.

4. **Real-Time Notifications:**
   - **Telegram Alerts:**  
     Users receive Telegram notifications when:
     - An ad is picked (i.e., when a transaction is initiated).
     - Payment is confirmed and tokens are successfully transferred.
   - **On-Screen Updates:**  
     The dashboard and ad listings also show real-time status updates.

5. **Customer Support & Chat:**
   - A built-in live chat box is available on every page for quick support.
   - A dedicated support portal provides FAQs, ticket submission, and troubleshooting guides.

## FEATURES
- **Wallet Integration**: Effortlessly connect your Stark-based wallet for smooth transactions.
- **Orders**: Access available orders, place personalized orders, and manage your trades with ease.
- **Chat Box**: Engage directly with potential traders through our integrated chat system.
- **Help and FAQ**: Find quick answers and guidance whenever you need it.
- **Customer Support**: A dedicated support team is on standby around the clock to resolve any issues and ensure a hassle-free experience.

  
#### Extra Features:

- Multi-Currency Support: Enable conversion between any fiat currency and cryptocurrency but also among various crypto assets.

- Automated Matching: An intelligent matching system that suggests the best available trades based on user preferences.

- Analytics & Insights: Access real-time market data.

- Dispute Resolution: A robust mechanism for conflict resolution and mediation to handle any transaction issues efficiently.


## SETUP & INSTALLATION
```
 git clone https://github.com/KingFRANKHOOD/P2P-Net.git
 cd P2P-Net
```
```
yarn install && yarn init
```
```
yarn dev
```
