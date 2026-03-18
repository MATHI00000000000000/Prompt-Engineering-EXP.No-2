EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:
Text Summarization across diAerent 
platforms 
Blockchain technology is a decentralized, distributed, and immutable digital ledger 
designed to record transactions across a network of computers, ensuring that records 
cannot be altered retroactively. Unlike traditional databases, which rely on a centralized 
authority, blockchain operates through a peer-to-peer network (nodes) where all 
participants maintain a shared copy of the data, thereby eliminating single points of 
failure and enhancing transparency. 
The "block" in blockchain refers to a data structure that groups transactions, 
timestamps, and a cryptographic hash—a unique identifier—linking it to the preceding 
block. This linkage forms a continuous chain. A fundamental security feature is that if a 
block is altered, its cryptographic hash changes, breaking the chain and notifying the 
entire network of the tampering attempt. 
To achieve consensus on the validity of new entries, blockchain networks utilize 
consensus mechanisms, such as Proof of Work (PoW) or Proof of Stake (PoS), requiring 
network agreement rather than trusting a single intermediary. Furthermore, "smart 
contracts" are frequently employed; these are self-executing programs stored on the 
chain that automatically execute transactions when predefined, coded conditions are 
met, further reducing the need for trusted third parties. 
The technology is classified into public (permissionless) networks, such as Bitcoin, 
which are open to all, and private (permissioned) networks, often used in enterprise 
supply chain or finance applications to restrict access while maintaining the benefits of 
immutability. Ultimately, blockchain provides a secure, transparent, and auditable 
method for tracking assets and digital interactions without central control. 
AI Platforms Used: 
• ChatGPT (OpenAI) 
• Gemini (Google) 
• Copilot (Microsoft) 
• Perplexity (Perplexity AI, Inc.) 
Execution: 
Each platform received the same article and was prompted with each technique. 
Outputs and processing times were recorded for comparison. 
Evaluation Criteria: 
• Accuracy: Correctness in capturing the article’s key points. 
• Coherence: Logical sequencing and readability. 
• Simplicity: Accessibility of language for undergraduate students. 
• Speed: Time taken to generate the summary. 
• User Experience (UX): Interface intuitiveness and ease of saving output. 
Each criterion was scored on a scale from 1 (poor) to 5 (excellent). 
Prompting Techniques Defined: 
 1.Zero_shot prompting: 
Prompt: 
 summarize the  text without example 
Responses generation buy AI Tools: 
ChatGPT: 
Blockchain is a decentralized, distributed, and immutable digital ledger 
used to record transactions across a network of computers. It operates 
through a peer-to-peer network, where all participants maintain a shared 
copy of the data, improving transparency and removing the need for a 
central authority. 
Transactions are grouped into blocks that contain data, timestamps, and a 
cryptographic hash linking each block to the previous one, forming a secure 
chain. If any block is altered, the hash changes, which reveals tampering 
and protects the integrity of the ledger. 
Blockchain networks rely on consensus mechanisms to validate new 
records and may use smart contracts, which automatically execute 
transactions when predefined conditions are met. The technology can 
function in public or private networks and provides a secure, transparent, 
and auditable system for recording digital transactions without central 
control. 
Google Gemini: 
Blockchain Technology Overview 
Blockchain is a decentralized, distributed ledger system that records data 
across a peer-to-peer network. By removing the need for a central authority, 
it eliminates single points of failure and ensures all participants have access 
to a shared, transparent record of data. 
Core Structural Features 
 Immutability: Data is organized into blocks containing a cryptographic hash 
that links to the previous entry. Any attempt to alter a block changes its 
hash, breaking the chain and alerting the network. 
 Consensus Mechanisms: Validity is determined through network-wide 
agreement protocols rather than a single intermediary. 
 Automation: Self-executing programs can be integrated into the chain to 
trigger actions automatically once specific conditions are met. 
Accessibility and Function 
The technology is divided into permissionless networks, which are open to 
everyone, and permissioned networks, which restrict access to specific 
users. Regardless of the type, the primary goal is to provide a secure, 
auditable, and transparent method for tracking digital interactions without 
central control. 
Microsoft copilot: 
Blockchain is a decentralized and immutable digital ledger that records 
transactions across a peer-to-peer network, ensuring transparency and security 
without reliance on a central authority. Data is stored in linked blocks secured by 
cryptographic hashes, making tampering detectable. Consensus mechanisms 
validate new entries collectively, while smart contracts automate processes. 
Blockchain can be public, open to all, or private, restricted to specific participants, 
and it provides a secure, transparent, and auditable way to manage digital 
interactions and assets. 
 2. Few-shot Prompting: 
Prompt: 
•Summarize the text with giving two or three examples 
Responses generation buy AI Tools: 
ChatGPT: 
Blockchain is a decentralized and secure digital ledger that records 
transactions across a network of computers without relying on a central 
authority. Data is stored in blocks that are connected using cryptographic 
hashes, forming a chain that prevents tampering and ensures transparency. 
The system uses consensus mechanisms to verify transactions, and smart 
contracts can automatically execute actions when certain conditions are 
met. Blockchain can operate in public or private networks depending on 
access and usage. 
Examples: 
 Bitcoin uses a public blockchain to record and verify digital currency 
transactions. 
 Supply chain management systems use private blockchains to track 
products and ensure transparency in the movement of goods. 
 Financial services use blockchain to securely record and verify digital 
transactions between institutions. 
Google Gemini: 
Blockchain is a decentralized and immutable digital ledger. Instead of relying on a 
single central authority to manage data, it uses a network of computers (nodes) 
where every participant holds a copy of the records. This structure ensures 
transparency and prevents any single point of failure. 
How it Works 
 The Chain: Data is grouped into "blocks" that include a timestamp and a 
cryptographic hash. Each block links to the one before it; if data is tampered 
with, the hash changes, breaking the chain and alerting the network. 
 Consensus: The network must agree on new entries through specific 
protocols, removing the need for a middleman. 
 Automation: Pre-coded, self-executing programs handle transactions 
automatically when specific conditions are met. 
Examples from the Text 
The passage highlights three key ways these concepts are applied in the real world: 
 Bitcoin: This serves as the primary example of a public (permissionless) 
network, which is open to any user globally. 
 Smart Contracts: These are the self-executing programs mentioned that 
automate transactions without requiring a trusted third party. 
 Enterprise Supply Chains: The text cites this as a use case for private 
(permissioned) networks, where access is restricted to specific participants 
while still maintaining a secure, auditable record. 
Microsoft copilot: 
Blockchain is a decentralized and immutable ledger that records transactions 
across a peer-to-peer network, removing the need for a central authority. Data is 
stored in linked blocks secured by cryptographic hashes, making tampering 
detectable. Consensus mechanisms like Proof of Work or Proof of Stake validate 
new entries collectively, while smart contracts automate processes. 
For example: 
 Bitcoin uses a public blockchain with Proof of Work to secure transactions. 
 Ethereum employs smart contracts to enable decentralized applications. 
 Enterprise supply chains often use private blockchains to track goods 
securely and transparently. 
 3. Chain Of Thought Prompt: 
Prompt: 
•Based on the above two summarization, give me the detailed summary of 
block chain Technology. 
Responses generation buy AI Tools: 
ChatGPT: 
Blockchain technology is a decentralized, distributed, and immutable digital ledger 
used to record and store transactions across a network of computers. Unlike 
traditional systems that depend on a central authority, blockchain works through a 
peer-to-peer network where every participant maintains a shared copy of the 
ledger. This structure improves transparency, reliability, and security, while 
removing the risk of a single point of failure. 
In blockchain, transactions are grouped into blocks. Each block contains 
transaction data, a timestamp, and a cryptographic hash that connects it to the 
previous block. This linking process forms a continuous chain of blocks. Because 
each block depends on the hash of the previous one, altering any data in a block 
would change its hash and break the chain, making tampering easily detectable 
across the network. 
To add new blocks, blockchain networks rely on consensus mechanisms. These 
mechanisms ensure that all participating nodes agree on the validity of 
transactions before they are permanently recorded. Instead of trusting one central 
authority, the network collectively verifies and confirms the data, which increases 
trust and integrity in the system. 
Another important feature of blockchain is the use of smart contracts. Smart 
contracts are self-executing digital programs stored on the blockchain that 
automatically perform actions when specific conditions are met. This automation 
reduces the need for intermediaries and helps ensure that agreements are 
executed accurately and transparently. 
Blockchain systems can be categorized into public (permissionless) and private 
(permissioned) networks. Public networks allow anyone to participate and validate 
transactions, while private networks restrict access to selected participants, often 
for organizational or enterprise use. 
Blockchain technology is widely applied in diAerent fields. For example, Bitcoin 
uses blockchain to securely record and verify digital currency transactions. In 
supply chain management, blockchain helps track products from production to 
delivery, improving transparency and reducing fraud. In financial services, 
blockchain enables secure and eAicient transaction records between institutions. 
Overall, blockchain provides a secure, transparent, and tamper-resistant system 
for recording digital transactions and managing data without relying on a 
centralized authority. 
Google Gemini: 
Combining the structural principles and the practical applications from the 
previous summaries, here is a detailed breakdown of blockchain technology as 
described in the passage. 
 Fundamental Nature and Structure 
 Blockchain is a decentralized, distributed, and immutable digital ledger. 
Unlike traditional databases that rely on a central authority, blockchain 
operates through a peer-to-peer (P2P) network of nodes. 
 Shared Record-Keeping: Every participant maintains a copy of the data, 
which eliminates "single points of failure." 
 The "Block" Linkage: Data is grouped into blocks containing transactions, 
timestamps, and a cryptographic hash. 
 Security through Connection: Each block includes the hash of the preceding 
block. If any data is altered, its hash changes, breaking the chain and 
immediately notifying the network of the tampering attempt. 
 Operational Mechanisms 
 To ensure the integrity of the ledger without a middleman, the technology 
relies on two primary functional components: 
 Consensus Protocols: New entries are only validated when the network 
reaches an agreement. The text identifies two main types: Proof of Work 
(PoW) and Proof of Stake (PoS). 
 Smart Contracts: These are self-executing programs stored directly on the 
chain. They automatically trigger transactions once predefined, coded 
conditions are met, further removing the need for third-party intermediaries. 
3.Classifications and Real-World Applications 
The passage categorizes blockchain based on accessibility and intended use: 
Summary Conclusion 
Ultimately, blockchain provides a secure, transparent, and auditable framework for 
tracking assets and digital interactions. By combining cryptographic security with 
network-wide consensus, it allows for trustless interactions where the technology 
itself—rather than a central institution—guarantees the validity of the data. 
Microsoft copilot: 
Core Concept 
Blockchain is a decentralized, distributed, and immutable digital ledger that 
records transactions across a peer-to-peer network. Unlike traditional databases 
managed by a central authority, blockchain ensures transparency and security by 
allowing all participants (nodes) to maintain a shared copy of the data. 
Structure 
 Blocks: Each block contains transaction data, a timestamp, and a 
cryptographic hash. 
 Chain: Blocks are linked together, with each new block referencing the hash 
of the previous one. 
 Tamper Resistance: Any alteration changes the hash, breaking the chain and 
alerting the network. 
Security & Consensus 
 Consensus Mechanisms: 
o Proof of Work (PoW): Requires computational eAort to validate 
transactions. 
o Proof of Stake (PoS): Validators are chosen based on their stake in the 
network. 
 These mechanisms ensure agreement across the network without relying on 
a single intermediary. 
Smart Contracts 
Self-executing programs stored on the blockchain that automatically enforce 
agreements when predefined conditions are met. They reduce the need for trusted 
third parties and enable decentralized applications. 
Types of Blockchains 
 Public (Permissionless): Open to anyone, e.g., Bitcoin and Ethereum. 
 Private (Permissioned): Restricted access, often used in enterprises for 
supply chain management or finance. 
Examples 
 Bitcoin: A public blockchain using PoW to secure peer-to-peer digital 
currency transactions. 
 Ethereum: A blockchain platform that popularized smart contracts and 
decentralized applications. 
 Enterprise Supply Chains: Private blockchains track goods transparently, 
ensuring authenticity and reducing fraud. 
Overall Significance 
Blockchain provides a secure, transparent, and auditable system for managing 
digital interactions and assets. By eliminating central control, it enhances trust, 
reduces single points of failure, and opens possibilities for innovation across 
f
inance, logistics, healthcare, and beyond. 
 Role-Based Prompt: 
Prompt: 
Consider you are a Researcher in the institution and now summarize the 
passage in that role perspective. 
Responses generation buy AI Tools: 
ChatGPT: 
Summary from a Researcher’s Perspective 
From a research standpoint, blockchain technology can be understood as a 
decentralized and distributed digital ledger system that enables secure, 
transparent, and tamper-resistant recording of transactions across multiple 
network nodes. Unlike traditional centralized databases, blockchain eliminates 
reliance on a single authority by maintaining a synchronized copy of the ledger 
among all participants in the network. 
Structurally, blockchain organizes data into blocks, each containing transaction 
details, timestamps, and a cryptographic hash that links it to the preceding block. 
This cryptographic linkage forms a continuous chain, ensuring data integrity 
because any modification in a block would change its hash and invalidate the 
chain. This property makes blockchain particularly valuable for systems that 
require high levels of data security, traceability, and auditability. 
Another key research focus is the consensus mechanism, which enables 
distributed participants to agree on the validity of transactions before they are 
added to the ledger. These mechanisms ensure trust within decentralized 
environments without depending on centralized intermediaries. Additionally, smart 
contracts extend the functionality of blockchain by enabling automated execution 
of predefined rules or agreements directly on the network. 
From an institutional and application perspective, blockchain systems can be 
implemented as public (permissionless) or private (permissioned) networks 
depending on the required level of access and control. Public networks are open to 
all participants, while private networks restrict participation to authorized entities, 
often making them suitable for enterprise or organizational environments. 
In practice, blockchain has demonstrated significant potential across several 
domains. For example, Bitcoin uses blockchain to maintain a transparent and 
secure digital transaction ledger. Similarly, supply chain management systems 
apply blockchain to improve traceability and accountability in product movement. 
In financial services, blockchain supports secure and eAicient transaction 
verification between institutions. 
Google Gemini: 
Research Synthesis: Architectural Integrity of Blockchain Systems 
Decentralized Ledger Topology 
Blockchain represents a paradigm shift from centralized data management to a 
distributed, peer-to-peer (P2P) architecture. By utilizing a network of nodes where 
all participants maintain a synchronized copy of the data, the system eAectively 
mitigates single points of failure. This decentralization ensures high availability and 
environmental transparency across the entire network. 
Cryptographic Continuity and Immutability 
The data structure is defined by its chronological "chaining" mechanism. Each 
discrete block contains a payload of transactions, a temporal metadata 
(timestamp), and a cryptographic hash. 
 The Linkage Principle: The hash of a block is intrinsically linked to its 
predecessor. 
 Integrity Verification: In a research context, the primary security feature is 
the sensitivity of the hash; any retroactive alteration of a block invalidates 
its hash, thereby breaking the sequence and triggering a network-wide alert 
of unauthorized tampering. 
Consensus and Programmable Logic 
To maintain a "trustless" environment—where participants do not need to trust a 
central intermediary—the system employs specific technical protocols: 
 Validation Protocols: Mechanisms such as Proof of Work (PoW) and Proof of 
Stake (PoS) shift the burden of validation from a single entity to a collective 
network agreement. 
 Smart Contracts: These represent the programmability of the ledger. They 
are self-executing, coded programs that automate transaction logic once 
predefined conditions are satisfied, reducing reliance on third-party legal or 
f
inancial intermediaries. 
Taxonomy of Network Access 
The research identifies a dual-classification system based on accessibility: 
 Permissionless (Public): Designed for total transparency and open 
participation (e.g., Bitcoin). 
 Permissioned (Private): Optimized for enterprise-level applications, such as 
f
inance and supply chain management, where data privacy and restricted 
access are prioritized without sacrificing the benefits of an auditable, 
immutable record. 
Conclusion 
From a research perspective, blockchain is not merely a database but a robust, 
auditable framework for secure asset tracking. It replaces institutional trust with 
mathematical and algorithmic certainty, providing a verifiable record of digital 
interactions. 
Microsoft copilot: 
Research-Oriented Summary of Blockchain Technology 
Blockchain represents a decentralized and immutable ledger system designed to 
record and verify transactions across distributed networks without reliance on a 
central authority. Its architecture is built on sequentially linked blocks, each 
containing transaction data, timestamps, and cryptographic hashes. This structure 
ensures integrity, as any modification disrupts the chain and is immediately 
detectable by the network. 
Consensus mechanisms, such as Proof of Work (PoW) and Proof of Stake (PoS), 
provide collective validation of new entries, reinforcing trust in the absence of 
intermediaries. Additionally, smart contracts—self-executing code embedded 
within the blockchain—enable automated enforcement of agreements, reducing 
human oversight and enhancing eAiciency. 
From a classification perspective, blockchains are divided into public 
(permissionless) systems, exemplified by Bitcoin and Ethereum, which allow open 
participation, and private (permissioned) systems, often adopted in enterprise 
contexts like supply chain management and financial services, where access is 
restricted but transparency and immutability are preserved. 
Research Significance 
 Security & Transparency: Provides tamper-resistant records, crucial for trust 
in digital ecosystems. 
 Automation: Smart contracts advance decentralized applications and 
reduce reliance on intermediaries. 
 Applications: Ranges from cryptocurrencies to enterprise solutions, oAering 
fertile ground for interdisciplinary research in computer sciene

![WhatsApp Image 2026-03-12 at 11 35 16 AM](https://github.com/user-attachments/assets/90e6afd5-4d16-4bda-8b58-829bf0143096)

RESULT:
Thus the summarization of all three different AI platforms has been executed and compared.
