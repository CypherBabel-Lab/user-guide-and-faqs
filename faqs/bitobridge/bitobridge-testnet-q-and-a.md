# BitoBridge Testnet Q\&A

## Q1. How to use the BitoBridge Testnet?

A1. You can check out the detailed steps by visiting the user guide on Medium:&#x20;

{% embed url="https://medium.com/@bitomni/bitobridge-testnet-guide-2b457a52c4d9" %}

## Q2. Why does a BTC Bridge transaction take longer to complete?

A2. The bridge from BTC to another blockchain, e.g., Ethereum, consists of two periods:

1. Bitcoin blockchain confirmation: there is a required number of confirmations on the Bitcoin blockchain. 6 confirmations for the Livenet (\~60 mins) or 3 confirmations for the Testnet (time varies).
2. Target chain confirmation: the period varies depending on the target chain.

Please be patient. The transaction status will be updated in the 'Bridging History' table.

## Q3. Why does it show 'Insufficient BTC UTXO' when signing with the Unisat wallet?

\
A3. This usually happens when the balance is lower than the "bridge amount + gas fee." Reserve enough gas in your wallet to ensure the transaction goes smoothly.

## Q4. Why does it show an 'Unknown error' when using the ICP Bridge?

A4. Typically, this message means that the RPC node has reached its limit due to a large number of transactions. Please try again later.

## Q5. Why didn't my balance update on the target chain after I finished the bridging?

A5. This is because the transaction needs to be confirmed on the target chain. For instance, the Bitcoin testnet needs 3 confirmations. The "successful" does not mean the confirmations on the target chain have succeeded. It only means the transaction has been successfully submitted to the target chain.

## Q6. Issues with IC Wallets?

A6. If you use Internet Identity, you will experience a short valid connection period. We will extend the connection in the coming updates.

For the Plug wallet, there are inherent issues that we cannot solve.

We plan to integrate more IC wallets to mitigate the wallet UX issue.

## Q7. Does the Bitomni bridge support other tokens on ICP for bridging?

A7: BitoBridge can support any ICRC1/ICRC2 token, meaning all the IC tokens. They are not shown on the testnet since we do not have their test tokens. However, they will be on the mainnet.
