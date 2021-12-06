# Cross-Boarder-Money-Transfer-using-Blockchain
Abstract 
For a long time, blockchain has been the talk of the town, and the 'distributed ledger blockchain' has 
been widely discussed by banks. Many banks and financial organisations have established innovation 
laboratories to undertake proof-of-concept tests in order to take use of new technology such as 
"blockchain" and "distributed ledger." According to industry surveys, regulatory and compliance 
challenges are the two most significant factors contributing to internal resistance to blockchain 
adoption, both of which must be addressed. 
An attempt to address this issue has been made from the standpoint of introducing an additional 
DATA Layer along the payment process chain including the blockchain. The regulatory and 
compliance requirements around transaction details for due transaction monitoring or confirming 
the details of the originator and recipient for FATF or 'sanction screening' can be implemented 
using the DATA Layer. Because the network is transparent, the number of suspicious 
transactions for AML and transactions through 'high risk countries' could be reduced.
1. Introduction 
1.1 Why this High-Level Design Document? 
HLD provides a high-level overview of the entire solution, product, system, platform service, or platform. 
High-Level-Design (HLD) is an architectural approach that defines architectural design in the context of a 
larger system. 
The primary goal of this document is to add the details required to describe the current project in order 
to represent a good coding model. This document also intends to aid in the identification of 
inconsistencies prior to coding and can be used as a reference for module interactions at the next level. 
Elements of HLD: 
 Overview Design element 
 High level information of every process and stage of the project. 
 Outline the user's daily process flow and performance needs 
 Includes the project's design elements and architecture. 
1.2 Scope of HLD 
The High-Level Design documentation presents the structure of the system as the application/database 
architecture, application flow and technology architecture. High-Level Design documentation may use 
some non-technical terms unlike Low Level design which should be strictly technical jargon.
2. General Description 
2.1 Product Perspective 
Blockchain is a digital ledger that keeps track of transactions. The name comes from the way the 
individual records, known as blocks, are connected together in a unified list known as a chain. The 
Blockchain technology guarantees the facilitation of rapid, safe, and low-cost cross-border payment 
processing services because each of these data blocks is encrypted and tied to each other utilising 
cryptographic principles. The technique can also be employed in "Anti-Money Laundering" situations. 
Blockchain technology has a bright future in cross-border payments because it employs encrypted 
distributed ledgers to allow verified real-time transaction verification without the usage of 
intermediaries like correspondent banks. It enables verification without the need for third-party 
verification. At the same time, technology will not eliminate the concept of banking because anyone can 
utilise it to integrate their product to their benefit. Some banks in Japan and Korea have already begun 
to use this technology for payment transactions. 
 
2.2 Problem Statement 
Remittance is a fund-transfer transaction wherein funds are moved from one account to another 
account within the same or any other financial institution. In a cross-border payment, SWIFT handles 
only the movement of messages along the payment chain. The correspondent banks do the actual 
debits and credits across accounts based on the message and help pass on the value to the final 
beneficiary. 
There are certain drawbacks with the current cross-border money transfer due to which a better 
technology is required for more efficient working of the system. The drawbacks are majorly:
 SWIFT was created to ensure and confirm message transmission because no two banks can 
agree on a transaction based on their own ledger. To ensure payments, central banks acted as 
settlement agents. 
 SWIFT bills the bank for processing payment orders, regardless of whether the bank is on the 
receiving or sending end of the transaction. 
 A single cross-border payment must pass through a number of correspondent banks, which are 
responsible for tasks such as receiving, aggregating, and netting payment messages before 
retransmitting confirmations and denials to the appropriate institutions. This lengthens the time 
it takes for things to settle. 
 To have a consistent perspective, a trustworthy third party with the ability to overwrite and 
overturn ledger activities was required. 
 The originator of the message is updated and populated by an internal bank account number in 
the case of a cross-border payment for a pooled account in certain banks. This raises concerns 
about the receiving bank's data protection and security. 
 
2.3 Proposed Solution 
Given the flaws in the current procedure for cross-border payments, blockchain and the concept of a 
distributed ledger have been gaining traction in the banking and finance industries. The distributed 
ledger blockchain has been generating a lot of excitement for a while now, and banks are also talking 
about it. 
Blockchain is a distributed network's universal ledger that is available to everyone in the network. There 
are critical factors that are used to address the industry-wide adoption of blockchain (distributed ledger 
technology): 
 Standardization – Lack of format standardization. We now have various global messaging 
standards, such as the Society for Worldwide Interbank Financial Telecommunication (SWIFT), 
Electronic Data Interchange For Administration (EDIFA) etc. 
 Cost and time benefit with added payment transparency – Cross-border payments are still 
costly. Charges incurred through many correspondent banks can be difficult to assess and 
determine. 
 Data protection and privacy – There is a stringent requirement to verify that no data breaches 
occur and that data is not altered at any stage along the chain. 
 Compliance and regulatory reporting – Adhering to the compliance and regulatory reporting like 
the anti-money laundering (AML), know your customer (KYC), financial action task force (FATF), 
and others in order to ensure there is sufficient payment transparency and to keep a tab on the 
high-risk corridors or high-risk payments. 
 Collaboration - Interoperability of blockchains will be achieved by collaboration among payment 
service providers. A large worldwide network is required.
3. Tools used 
Tools used in this project are: 
I. Python 
II. Jupyter 
III. GitHub 
 
4. Constraints and current challenges: 
 A single cross-border payment must pass through a number of correspondent banks, which are 
responsible for tasks such as receiving, aggregating, and netting payment messages before 
retransmitting confirmations and denials to the appropriate institutions. This lengthens the time 
it takes for things to settle. 
 To have a consistent perspective, a trustworthy third party with the ability to overwrite and 
overturn ledger activities was required. 
 The originator of the message is updated and populated by an internal bank account number in 
the case of a cross-border payment for a pooled account in certain banks. This raises concerns 
about the receiving bank's data protection and security. 
5. Assumptions: 
There are certain assumptions attached with the adoption of blockchain for cross-border 
payments: 
 Banks and financial institutions will accept blockchain as a better technology and incur 
the capex for change of technology as it would lead to standardization and cost reduction 
in future
 Industry study has revealed that the regulatory and compliance issues are the two biggest 
factors, which are believed to contribute towards internal resistance to adoption of blockchain 
and need to be duly addressed
 Reliance will be made on the technology for protecting consumer data as data privacy is of 
utmost importance for banks and financial institutions
6. Collaborative approach to regulatory reporting by leveraging big data 
It is thought that by providing an additional data layer throughout the payment process via the 
blockchain, the difficulty of maintaining regulatory compliance can be overcome. The registered details 
of the banks gathered for engaging into transactions within the permissioned blockchain nodes / 
networks must be absorbed in the data layer. 
Similarly, the blockchain transaction details must be consumed into the big data environment. Once 
these details are obtained, the data must be translated because it is in hash format, and a join with the 
bank's registered information will allow the specifics for each transaction to be extracted. 
7. Design Details 
7.1 Traditional Methodology: 
Remittance is a type of fund transfer in which money is transferred from one account to another within 
the same or another financial organization. SWIFT exclusively handles the transfer of messages along 
the payment chain in a cross-border transaction. The correspondent banks carry out the actual debits 
and credits across accounts in accordance with the message and assist in the transfer of money to the 
final beneficiary. Bank A, for example, is sending a euro sum to a euro account at Germany's bank D. The 
procedure is as follows:
• Bank A in the United States receives an MT103 (a SWIFT message format) in $US. 
• Bank A transmits a payment request by Fedwire to its correspondent bank, Bank B, along with a 
debit/credit instruction for further transmission. 
• Bank B makes the adjustments and sends a message over the SWIFT network to its correspondent 
bank, Bank C in Brussels. 
• Bank C sends the money to bank D in Germany via the Single Euro Payments Area (SEPA). 
• Bank D makes a EUR credit to the supplier's account. 
Banks incur fees for executing each transaction, as indicated in the payment flow chart (Figure 1), raising 
the expenses for all parties involved. SWIFT charges a fee for sending messages, which adds to the cost. 
Because the ledgers are local to the banks, SWIFT messages ensure that the debit entry from one bank's 
ledger is sent to another bank so that the equivalent credit entry can be passed / posted in its ledger. 
Fees on SWIFT messages rise in lockstep with the number of payment messages in the chain. The 
existing international payment/transfer system, which involves correspondent banks, has the following 
disadvantages: 
7.2 Disadvantages of Traditional Methodology: 
• SWIFT was created to guarantee and confirm message transmission because no two banks can agree 
on a transaction based on their own ledger. To ensure payments, central banks acted as settlement 
agents. 
• Regardless of whether the bank is on the receiving or sending end of the payment order, SWIFT 
charges the bank for processing it. 
• A single cross-border payment must pass through a number of correspondent banks, who are 
responsible for receiving, aggregating, and netting payment messages before retransmitting 
confirmations and denials to the appropriate institutions. This lengthens the time it takes for things to 
settle. 
• To have a consistent perspective, a trustworthy third party with the ability to overwrite and overturn 
ledger activities is required. 
• A central bank would usually require banks to retain sufficient liquidity in their settlement accounts or 
nostro accounts with them. 
8. Proposed methodology 
It is thought that by providing an additional data layer throughout the payment process via the 
blockchain, the difficulty of maintaining regulatory compliance can be overcome. The registered details 
of the banks gathered for engaging into transactions within the permissioned blockchain nodes / 
networks must be absorbed in the data layer. Similarly, the blockchain transaction details must be 
consumed into the big data environment. Once these details are obtained, the data must be translated 
because it is in hash format, and a join with the bank's registered information will allow the specifics for 
each transaction to be extracted. 
For intra-group payments, where payments are made between branches of the same bank or 
subsidiaries, the technique shown in Figure can be accomplished effortlessly. Intra-group traffic data is 
less scrutinized by regulators, and bilateral agreements are easier to reach. Domestic and cross-border 
intragroup payments are both possible. Interbranch payments within a country are classified as 
domestic, and interbranch payments between countries are classified as cross-border. The following 
transaction can be entered in the aforesaid setup, as shown in Figure. 
The connectivity must now be expanded as follows in order to extend this framework to the originator 
and beneficiary: 
The user logs in with their customer ID credentials, much like they do with internet banking. The hashed 
account number of the originator and beneficiary is included in the transaction's extra information. For 
regulatory reporting, the originator and beneficiary's information can be linked to the applicable 
customer information database to extract all relevant information such as name, address, and other 
personal information. Because the transaction is between network nodes, transactions along high-risk 
corridors will be limited or avoided. 
Customers are not given a unique address to connect to the node since it will reveal a copy of each 
customer's ledger to the other customers. Only bank accounts are part of network nodes due to the 
number of clients and to provide secrecy and data privacy to the user. The regulatory and compliance 
requirements around transaction details for due transaction monitoring or confirming the details of the 
originator and recipient for FATF or sanction screening can be implemented properly using the data 
layer. Because the network is transparent, the number of suspicious transactions for AML and 
transactions through high-risk countries is reduced. The following are some of the advantages of 
implementing a data layer enabled by big data: 
 Data ingest to the blockchain, such as customer and registration information, can be 
automatically scooped or relocated to the big data environment once it has been planned and 
mapped from the source system tables. As illustrated in the diagram above, three transactions 
can be posted. Transactions are recorded on the blockchain. Bank A has posted the transaction. 
 In the big data context, the joining of the underlying customer details with the hashed 
transactions in the block can also be done without breaking the chain. The details that aren't in 
hash format are what regulators want to see. As a result, a mechanism to either push a 
duplicate of the transaction before it is hashed or attach it to a blockchain block can be 
considered. 
 A self-service business intelligence (BI) strategy can be used, in which a set of users will be given 
access to data visualization tools and will be able to slice and dice data according to their needs 
without having to move the data out of the environment. This guarantees that data governance 
is in place, as well as assisting regulators, compliance, and other departments in conducting 
independent data studies. 
 Data can be partitioned by location, country, and date in a big data environment, making 
housekeeping easier and cleaner. 
 Because the transaction data is in a big data environment, the FATF automation may be properly 
planned and implemented, confirming the originator and beneficiary's details on name, address, 
and account-related details. 
9. Advantages of using Blockchain for cross-border money transfer 
 It results in any middlemen, central agencies, or correspondents being excluded from payment 
processing. The transaction takes place between parties that have entered into a bilateral 
agreement, guaranteeing that confidence is established.
 Lower costs with fewer fees along the payment chain. In addition, if the messages are routed 
through SWIFT, it charges for the processing of the messages. As a result of these fees, 
correspondent banks and central agencies increase the cost of processing payments by receiving, 
aggregating, and netting payment messages before retransmitting confirmations and denials to the 
appropriate banks.
 There is no need for central agencies or message transfer, resulting in a faster settlement time.
 The central banks are not required to ensure intraday liquidity. The balances are properly 
maintained because it is a distributed ledger and each node of the network has a copy of the 
balances as they are kept in the settlement accounts with the other banks.
 Because the transaction details are encrypted and hashed, there is almost no way to change the 
data.
 Because no communications are sent, the issues associated with standardisation are also reduced.
 Increased payment transparency with distributed ledger because the sender and receiver are the 
network's / chain's nodes.
 The difficulties of data security and privacy could be solved to some extent by using a private or 
permissioned blockchain, where no one can join the network and become a node anonymously. 
Such an arrangement will necessitate the parties registering or entering into a bilateral agreement, 
and accessing transactions via a private key shared among the network's trustworthy participants. 
Also, everyone is aware of how difficult it is to hack the block's underlying hashed transactions.
10. Conclusions
The best way to get started is by moving with caution using a stepwise approach. 
• It is best to get the dice rolling for blockchain for intra-group payments first. The implementation 
will help banks/financial institutions immediately with the costs involved in the generation and 
processing of the different messages. Given the volumes per day, it is a step-in cost saving and 
reduced turnaround time as also to experience the benefits of the modern-day technology of 
blockchain and distributed ledger. Also, given that the scope is around intra-group payments, this 
would bring in a comfort factor to the banks as the boundaries of the payments are known. 
• Once intra-group payments are executed with payments between banks, the process can be 
expanded to customer payments within the intra-group traffic, before taking it extensively to the 
external correspondents. 
