# Bitcoin Peer-to-Peer Lending Platform

A trustless Bitcoin lending platform that allows peers to lend money directly to one another with agreed-upon terms without involving a third party. 

Users create a special purpose pseudonymous wallet used to loan funds and pay back loans. Each wallet is associated with its lending history, allowing potential lenders to evaluate the wallet’s risk before making each loan. Borrowers are incentivized to maintain a positive lending history in order to attract lenders and qualify for lower rates. 

The intent of this platform is to provide access to capital to everyone in the world using the unstoppable currency of Bitcoin. Many people in the world do not have access to capital at all: the unbanked, individuals and small businesses in developing nations or underserved areas, and people who wish to opt out of the fiat economy. This platform provides a way for two parties anywhere in the world to enter into a lending agreement, and it provides a safe framework for risk evaluation and loan repayment. 

## Lending Transactions

A transaction is started by a user making an offer. An offer can be either to lend or to borrow a certain amount of Bitcoin. This offer would contain specific terms including date(s) and schedule of repayment, repayment amount, and the amount of deposit to be used as collateral. A second user would review the terms and accept the offer. 

Once accepted and signed by both parties, the offer becomes a bonded transaction and is published to the blockchain. 

When the loan is paid back according to the terms, another transaction is created, recording the successful completion of the loan. 


## Wallet

A pseudonymous wallet functions much like a conventional Bitcoin wallet. In addition to storing the ledger of transactions, the wallet records the user’s lending and borrowing history, which is used to compute a creditworthiness score. 

Lenders can use information contained in the wallet to judge the risk of potential borrowers. Borrowers’ wallets who have a history of successful repayment will be judged as low risk, and may qualify for lower interest rates. Wallets with limited history or who have failed to abide by loan terms will be perceived as high risk. 

## Credit Score

The borrower’s wallet contains a list of completed transactions, the amount of each loan, and its outcome. A creditworthiness score is computed based on the number of loans, the volume of money borrowed, the age of loans, and the ratio of successful to failed repayments. 

## Making an Offer and Defining Terms

Loan terms are determined by the user making the offer. The offer can be either to lend or to borrow Bitcoin. An offer can have the following elements: 

- Amount of loan
- Repayment schedule
- Interest rate or flat repayment fee
- Collateral deposit (predetermined amount or percent of the loan)

## Incentives

Any lender can view the borrower wallet to evaluate their creditworthiness score and evaluate their risk. 

Borrowers are incentivized to repay their loans according to terms in order to qualify for future and grafter loans. 

First time borrowers should start by borrowing a very small amount of money in order to establish credit.

New and very young wallets will require a higher interest rate than well-established wallets. Lenders may choose to take the risk to lend a small amount to a younger wallet in order to make a higher return on the investment. 

After a wallet has established a high creditworthiness score, they may request larger loans with lower interest. Lenders will see this as less risky.

Borrowers are disincentivized from creating throwaway wallets in order to stairstep up to scam a larger amount of money because each loan has a cost in the form of interest. Lenders should not loan (and borrowers should not request) more than the total amount of interest that a borrower has paid over time. In this way the stairstep scam becomes uneconomical. 

### Arbitration
Arbitration would be handled by the community, with arbitrators being chosen randomly from the pool. Arbitration participants would be compensated from the funds made available by the collateral deposit. Arbitration may have several outcomes: 1) in the worst case, the loan may be forfeit, in which case the lender does not receive their funds. 2) The parties may agree to modified payment terms, such as extended payback date, etc. Modified payment terms must be secured by an additional collateral deposit by the borrower. 

### Collateral Deposit
This collateral deposit is optional, and guarantees that if Bob is unable to repay his loan, he will have recourse to arbitration. Lenders will be more likely to accept his offer if he provides collateral. 

### Example 
Bob would like to borrow one Bitcoin, and Alice has one Bitcoin that she would like to lend. Bob creates an offer to borrow one BTC. In his terms he states that he will pay back 1.1 BTC in six months. To secure this offer, Bob optionally pays an additional 0.1 BTC as a collateral deposit. If Bob pays back his loan successfully, he will get this 0.1 BTC back at the completion of the transaction. At the end of his loan, Bob pays 1.1 BTC back to Alice. Both users’ wallets are signed with the successful transaction. 

Bob’s business is growing and he wants to take out another loan. Bob looks at the list of loans offered, and selects a 2 BTC loan offered by Carol. Carol receives a request by Bob to accept her offer, and she can see that Bob (pseudonymously) has successfully repaid a similar loan, so she believes that Bob is a good risk. She accepts his request, and Carol and Bob enter into the transaction. 

## Strictly Bitcoin

All money on this platform stays in Bitcoin, and no currency conversion or sale of currency is ever performed. Funds are loaned in Bitcoin, and loans are repaid in Bitcoin. 

If a particular user wants to convert their coins to fiat, those coins can be transferred to another wallet or to an exchange. 

## Similarities to Bisq

This platform is similar in many ways to Bisq. However, unlike Bisq, no conversion to fiat is performed. 

We all love Bisq, but the user interface is geared towards technical users. Bisq has a steep learning curve that may prevent many users from ever completing a transaction. Our aim is to build a platform that is easy to use and has a shallow learning curve.
