# Wendel Pereira

**Email**: [as2742397@gmail.com](mailto:as2742397@gmail.com)  
**LinkedIn**: [linkedin.com/in/wendelrpereira](https://www.linkedin.com/in/wendelrpereira/)  
**Telegram**: [@bitdeep](https://t.me/bitdeep)  
**Twitter**: [@bitdeep_oficial](https://twitter.com/bitdeep_oficial)  
**Discord**: **bitdeep**  
**GitHub**: [github.com/bitdeep](https://github.com/bitdeep)

---

## My Dream

_Having a **$1B protocol TVL** that I at least helped to code._

---

## Summary

I’m an already seasoned blockchain developer with a deep understanding of smart contract and Bitcoin development as I’m in the field since the **“colored coins”** and **“masternode”** revolution, even before _The Pandemic_.

My involvement in blockchain technology predates Ethereum. In the early days of Bitcoin, I was an active participant in the Bitcoin forum, contributing my expertise in **C++/QT** development. I assisted teams working on masternodes and privacy coins, as these applications were primarily built using **C++/QT** at that time as I had lots of experience in **C++** from my telecom background.

After masternodes and privacy coins fallout, I moved to **EVM** during **SUSHI DEX** rise up, helping here and then, assisting teams in the farming era.

Right now, my focus is more on **decentralized finance (DeFi)**, working on new edge protocol deployments on EVM chains, especially on **Cosmos/EVM protocols**.

Also, sometimes, I integrate **AI and DeFi**, like the **[$NAAI protocol](https://etherscan.io/token/0x7865ec47bef9823ad0010c4970ed90a5e8107e53#code)**, where I created their entire backend for an "AI auditing contract" solution and coded their smart contract with some nice anti-snipe bot features.

So far, until today, no protocol has been hacked as I’m very careful with Solidity coding and ensure **full test coverage** and I never deploy a protocol without full testing it with test-cases.

---

## 🛠 Skills & Expertise

## 💡 Smart Contract Development

- Developed smart contracts for **DeFi protocols**, DEXs, betting platforms, and decentralized exchanges
- Implemented complex interactions like **flash loans** and **atomic swaps**
- Extensive experience with **proxy deployments** and upgradeable contracts
- Implemented various proxy patterns including **UUPS**, **Transparent**, and **Beacon** proxies
- Developed and audited proxy contracts for major DeFi protocols
- Optimized gas costs for proxy implementations and upgrades, like, using beacons on gauges/pools deployments of factories.
- Managed complex upgrade processes for live protocols with minimal downtime, _as it needs to be done with very-very care_.
- Created custom proxy patterns for specific protocol requirements, such as developing a custom upgradeable beacon for [**Equilibre Finance**](https://equilibrefinance.com/) and other protocols

- Created presale, airdrop, and farming contracts with advanced features, as demonstrated in multiple repositories on my [GitHub profile](https://github.com/bitdeep), such as:
  - Sample public contracts in the [SolidityContracts](https://github.com/bitdeep/SolidityContracts) repository
  - Token-related contracts in repositories like [xex-contracts](https://github.com/bitdeep/xex-contracts) and [token-deposit](https://github.com/bitdeep/token-deposit)
  - Specialized contracts like the [timelock-multsig](https://github.com/bitdeep/timelock-multsig) combination, **as one of biggest issue of our time is hack of protocols with multiple multisigs**.
- Designed NFT auction and raffle systems, as demonstrated in various repositories on my [GitHub profile](https://github.com/bitdeep):
  - Implemented smart contracts for NFT minting, trading, and auctions in projects like [nft-auction](https://github.com/bitdeep/nft-auction)
  - Developed raffle systems with fair distribution mechanisms, such as [nft-raffle-contract](https://github.com/bitdeep/nft-raffle-contract)
  - Created NFT-based systems for gaming and betting, as seen in [nft-game-engine](https://github.com/bitdeep/nft-game-engine)
  - Implemented advanced features like preventing NFT reveals before minting in [nft-prevent-reveal-before-mint](https://github.com/bitdeep/nft-prevent-reveal-before-mint)
  - Developed NFT-related projects with various functionalities, such as [zogue-collection](https://github.com/bitdeep/zogue-collection) and [mint-o-taurs](https://github.com/bitdeep/mint-o-taurs)
- Developed DAO and treasury management contracts, as demonstrated in several repositories:
  - [dao-contracts-dev](https://github.com/bitdeep/dao-contracts-dev): DAO treasure contracts
  - [dao-team-presale](https://github.com/bitdeep/dao-team-presale): Team presale contracts and test-cases for DAO
  - [farm-with-lock](https://github.com/bitdeep/farm-with-lock): Farming contract with lock mechanism, often used in DAO ecosystems
- Implemented various DAO-related functionalities, as demonstrated in several repositories:
  - Voting mechanisms and governance systems in [dao-contracts-dev](https://github.com/bitdeep/dao-contracts-dev)
  - Token distribution systems, including team presales in [dao-team-presale](https://github.com/bitdeep/dao-team-presale)
  - Treasury management and allocation strategies
  - Governance proposal creation and execution processes
  - Farming contracts with lock mechanisms for token incentives in [farm-with-lock](https://github.com/bitdeep/farm-with-lock)
- Applied security best practices:
  - Implemented **reentrancy guards** and **access control mechanisms**
  - Utilized **OpenZeppelin** libraries for standardized and audited security features
  - Developed comprehensive test suites for smart contracts, as demonstrated in repositories like:
    - [dao-team-presale](https://github.com/bitdeep/dao-team-presale): Includes test cases for team presale contracts
    - [farm-with-lock](https://github.com/bitdeep/farm-with-lock): Features tests for farming contracts with lock mechanisms
  - Implemented advanced security measures such as:
    - Pause functionality for emergency situations
    - Time-locked operations for critical functions
    - Multi-signature requirements for high-value transactions
  - Conducted thorough audits and code reviews, utilizing a combination of AI-assisted tools and manual expertise:
    - Leveraged the [audit_gpt](https://github.com/bitdeep/audit_gpt) repository for AI-powered smart contract analysis
    - Employed Google Gemini for advanced code review and potential vulnerability detection
    - Utilized Aider for collaborative code review sessions and automated test case generation
    - Complemented AI-assisted reviews with manual expert analysis to ensure comprehensive security assessments
  - Implemented advanced anti-bot and anti-MEV measures in token contracts, as demonstrated in projects like [$NAAI protocol](https://etherscan.io/token/0x7865ec47bef9823ad0010c4970ed90a5e8107e53#code):
    - Utilized dynamic buy and sell limits to prevent large-scale sniping and dumping
    - Implemented cooldown periods between transactions to mitigate rapid trading by bots
    - Employed blacklisting functionality to restrict malicious actors
    - Integrated anti-whale mechanisms to prevent market manipulation by large holders
    - Implemented gas price limits to reduce the effectiveness of front-running attacks
    - Utilized transfer delays for large transactions to give legitimate traders a fair chance
  - Designed secure proxy patterns for upgradeable contracts, demonstrated in various DeFi protocol implementations:
    - Deployed numerous Transparent and Beacon proxies for major protocols
    - Implemented UUPS (Universal Upgradeable Proxy Standard) for gas-efficient upgrades
    - Created custom proxy patterns for specific protocol requirements, such as a upgradeable beacon for Equilibre Finance
    - Optimized gas costs for proxy implementations using techniques like minimal proxies (EIP-1167)
    - Managed complex upgrade processes for live protocols with minimal downtime
    - Implemented multi-step upgrade patterns for critical protocol changes, _like creating scripts to safe upgrade of gauges/pools of factories_.
    - Created very complex scripts for proxy deployment and explorer proxy verification on various chains.
  - Conducted thorough **unit and integration testing**:
    - Developed comprehensive test suites using Hardhat and Forge, ensuring full coverage of smart contracts, as demonstrated in repositories like [dao-team-presale](https://github.com/bitdeep/dao-team-presale) and [farm-with-lock](https://github.com/bitdeep/farm-with-lock)
    - Implemented advanced testing scenarios with forked mainnet environments to simulate real-world conditions, particularly useful for DeFi projects like [xex-contracts](https://github.com/bitdeep/xex-contracts)
    - Utilized Tenderly for detailed transaction tracing and debugging in complex test cases, enhancing the robustness of contracts such as those in [nft-auction](https://github.com/bitdeep/nft-auction)
    - Achieved consistently high test coverage rates, often exceeding 95% for critical contract functions, as seen in various DAO and NFT projects
    - Created parameterized tests to cover a wide range of input scenarios efficiently, particularly useful in projects like [nft-raffle-contract](https://github.com/bitdeep/nft-raffle-contract)
    - Implemented fuzz testing to identify edge cases and potential vulnerabilities, crucial for security-critical contracts like [timelock-multsig](https://github.com/bitdeep/timelock-multsig)
    - Designed integration tests to verify contract interactions within the broader ecosystem, as demonstrated in complex projects like [sushiswapV1](https://github.com/bitdeep/sushiswapV1)
    - Utilized time-manipulation techniques in Hardhat to test time-dependent contract logic, essential for projects with vesting or lock periods like [farm-with-lock](https://github.com/bitdeep/farm-with-lock)
    - Implemented gas usage tracking and optimization based on test results, crucial for efficient contract deployment and execution across various projects _as some contracts may not deploy if gas is not optimized_.
  - Optimized for **gas efficiency** and scalability:
    - _most of optimizations are in private contracts that I can share some if needed_.
    - Used storage packing to reduce slot usage where applicable
    - Applied `unchecked` blocks for safe arithmetic operations
    - Implemented bit manipulation for efficient flag storage
    - Used inline assembly for specific optimizations when necessary
    - Employed proxy patterns to minimize deployment costs
    - Utilized `calldata` for read-only function parameters
    - Optimized loops by caching lengths and using pre-increment
    - Leveraged short-circuiting in conditional statements
- Stayed current with latest **Solidity** features and best practices
    - I tend to use the latest version of Solidity, as I like to use the latest features and best practices.
    - Using latest versions with good test-cases is very important to ensure the security of the contracts and to demonstrate good practices used in the protocol.

## **🏗 Key Projects:**
- **Yield farming and liquidity mining protocols**
- **NFT marketplaces, minting, and gaming platforms**
- **Decentralized exchanges** (including work on SushiSwap)
- **ERC20 token implementations** with advanced features
- **Anti-sniper and anti-MEV protection systems**
- **Memecoin smart contracts** with unique tokenomics
- **Decentralized betting platforms**
- **Smart contract refactoring and optimization**

## 🔗 Bitcoin Development

- **Bitcoin Chain Monitoring**: Developed systems to detect and decode transactions for:
  - Payment tracking
  - Ordinals transactions
  - NFT minting on Bitcoin
- **Transaction Analysis**: Created tools for in-depth examination of Bitcoin transactions
- **Ordinals Protocol**: Implemented support for tracking and decoding Ordinals inscriptions
- **NFT Minting Detection**: Developed algorithms to identify and analyze NFT minting activities on Bitcoin
- **Real-time Blockchain Indexing**: Built efficient indexing systems for quick transaction lookups

## 💻 Programming Languages & Technologies

- **Solidity**: Expert-level smart contract development both for EVM and Cosmos/EVM protocols that has some quirks that needs to be handled.
- **TypeScript**, **JavaScript**, **Node.js**: Full-stack Web3 development for backend and cloud services, most oriented for blockchain explorers and bots and AI services.
- **React**: Frontend development for DApps, but not as much as I used to do, as I prefer to use **bootstrap+jquery** for my contract/ui tools.
- **C/C++**: Extensive experience in blockchain core development and VoIP services as I worked many years in telecom background developing VoIP systems.
- **Golang/Rust**: Prefer to avoid it and use C++/Qt for most of my projects.

## 🤖 AI and Blockchain Integration

- Developed an **AI-powered auditing system** for smart contract analysis
- Created tools for fine-tuning GPT models for blockchain-specific tasks, most of the time using RAG from database data.
- Implemented RAG-based document chatting systems for blockchain information, like, informaing use about contract issues using api like fuzzers, goplus, slither and other tools.
- Integrated AI capabilities with DeFi protocols for enhanced security and user experience, specially for auditing contracts.

## 📞 VoIP Services Experience

- Designed and implemented **VoIP protocols** and architectures for large scale VoIP systems for callcenter and fed-gov telecom projects.
- Developed Softphone/VoIP applications using **C/C++**/Qt for various telecom projects.
- Optimized VoIP performance and scalability for telecom projects, to handle largue scale state calling queues for public safety answering points (P3).
- Troubleshot and resolved VoIP issues for telecom projects, specially in 3rd party integrations with VoIP vendors, enterprises and other telecom projects that needed state/wan/lan/internet connections.
- Worked with VoIP hardware and software, like, Cisco, Avaya, Mitel, etc for large scale telecom projects and fed-gov projects.
- Integrated VoIP systems with other telecommunications systems, like, CRM, billing, etc, specially to handle calls/queues/reports/analytics from CDR raw data with other tools like Microsoft Excel and Power BI.

**🏗 VoIP Projects:**
- **VoIP gateway** for PSTN/E1/IP to VoIP network connectivity
- **VoIP softphone** application for mobile devices
- **Softphone** application for desktops in C/pjsip/C++/Qt
- **Large governamental VoIP call center solution** with call queuing, reporting, and analytics
- VoIP system integration with **CRM system** with large governamental public services numbers with like 20.000 calls per day.

---

## Docker, Git, and Cloud Services and Deployment

## AWS

> _On cloud services, I worked with various cloud providers to deploy telegram/discord bot and AI services and also to pre/pos process VoIP data, like calls audios conversion and transcription._

- **Amazon ECS**: Managed container orchestration, specially for deploying my bots and AI services for large scale telegram/discord/telegram communities.
- **AWS CodeCommit** and **CodePipeline**: Git repositories and CI/CD automation.
- **AWS Lambda**: Used for deploying my bots and AI services for large scale telegram/discord/telegram communities.
- **GCP Gemini**: Used gemini for large scale AI processing of audios and other data for BI systems.

## Others

- **DigitalOcean** and **Spaces**: normaly I used it for some projects when asked by team, but not as much as AWS.
- **Heroku Container Registry**, **Pipelines**, and **Review Apps**: normaly I used it for some projects when asked by team, but not as much as AWS.

---

## Blockchain Protocols

Experience with various blockchain protocols:

- **Layer 0**: Deployed both ERC20 and ERC721 bridgeable tokens for the xexlabs.com protocol, demonstrating proficiency in cross-chain interoperability and token standards implementation.
- **Arbitrum**: Worked on layer 2 scaling solutions, also using L0 to bridge tokens to Arbitrum.
- Other protocols: Familiar with a range of blockchain ecosystems and their unique features, as I worked for various teams deploying on Cosmos/EVM layers, there is very very specific quirks that needs to be handled during the deployment process.

---

# Open Source Contributions

- Actively maintain 67 public repositories on GitHub as example for anyone to learn and use them, I keep them there just to help the community and to show my skills and knowledge.
- Contribute to major DeFi projects like SushiSwap and Abracadabra Money, Camelot, KOI, and various other small protocols that I love to help, speciall on meme coins sector.
- Develop and share utilities for blockchain interactions and Web3 development, like, bots, explorers, etc.
- Also, starting to contribute with AI NPM ecosystem.

# AI and Messaging Platform Integration

- **AI-Powered Bots and DeFi Integration**

    - Developed an **AI-powered auditing system** for the **$NAAI protocol**, integrating AI capabilities with smart contract analysis.
    - Created a sophisticated backend system to support AI-driven contract auditing, enhancing security in DeFi projects.
    - Implemented advanced anti-snipe bot features in smart contracts, leveraging AI to detect and prevent malicious activities.
    - Working on spare time:
        - a `gc` cli tool to help with git workflow and to make it easier to contribute to open source projects.
        - a `hn` cli tool to help with Hacker News that I use daily to keep up with the latest news in the tech world in a summarized way, telling me about author/site/points/comments and all the info in a summarized way to avoid scam and fake news.
        - a `aic` ai-aider tool to help with AI coding, like, code review, test case generation, etc. Where I have a prompt to instruct aider to do things to me, specially passing the entire relevant code context to be more efficient.
        - a `fs-ai` tool to help with file search in a summarized way, like, passing the dir, it give me the summary of the files and subdirs, and then I can choose to read more or not. And allow me to organize and index my files and folders.
        - a `ai-yt` tool to help with youtube, like, passing the url, it give me the summary of the video, and then I can choose what language I want it to convert the audio, givinging my own voice to the video (pt-br), so I can listen to the video in the car, etc.
        - a `ai-podcast` tool to help with youtube videos, like, passing the url, it give me the summary of the video, and then I can choose what language I want it to convert the audio, givinging my own voice to the video (pt-br), so I can listen to the video in the car, etc, it auto-add to my pocast queue to I can listen while I do my tasks.
        - a `gfs` a google chrome exteion that auto-check all my links in google search results, and tell me if it is a scam or not, and give me the summary of the page, and then I can choose to open the page or not.
        - a `ai-v`, an ai-powered translation that perfectly translate my videos with voice cloning, so I can watch any video in any language as if it was in my language (pt-br), and the voice is in portuguese (br) using artist tone.
        - a `ai-books-tts`, an ai-powered text to speech that perfectly convert any text to speech in any language with my own voice, I use it to convert papers/books to audio books and listen while I do my tasks/waking up.

## Telegram Bot Development

- Designed and built **custom Telegram bots** for crypto communities.
- Implemented bots providing real-time market data, wallet tracking, and automated support.
- Specially designed largue scale community bots with queueing system to process large scale of prompts, like, airdrops, airdrop claim, voting, etc.
- I have various samples to demonstrate my skills in telegram bots, like, airdrop bots, voting bots, etc.

## Discord Bot Development

- Developed **Discord bots** for DeFi projects.
- Created bots facilitating user engagement, token distribution, and community management.
- I have various samples to demonstrate my skills in discord bots, like, airdrop bots, voting bots, etc.

## AI-Enhanced Interactions

- Integrated AI-powered natural language processing to enhance bot interactions, specially using zod and gpt-4o to create schemas and validate data.
- Provided more intuitive user experiences through AI capabilities, using RAG to answer questions and to provide more accurate and up-to-date information.
- **Developed very personalized AI bots that can't be easily detected by users, specially for chating when it's need to know user preferences and to act as a good friend**.

## Blockchain Integration

- Created bots capable of executing on-chain transactions based on user commands, specially generating user wallet addresses and private keys to interact with the blockchain.
- Both on discord/tg, allowed users to verify and claim airdrops, voting, etc via bots.

## Cross-Platform Solutions

- Implemented solutions that synchronized data and functionality between Telegram, Discord, and web interfaces, specially for community bots that needs to be available 24/7 on multiple platforms.
- Integrated blockchain explorer and other APIs to allow users to check their balance, transactions, etc, directly from the bot interface.

## Security

- Developed secure authentication systems for bots.
- Normally I use aws secure vault to store my bots tokens and keys, and to avoid any leaks.
- Also, for local bots initialization I tend to use local vaults npm modules to store my keys and tokens, and to avoid any leaks, as I can use dotenv, I avoid it on VPS/cloud services.
- Ensured user data protection and prevented unauthorized access to sensitive functions by encrypting data at rest and implementing strict access controls using local vaults with PIN codes to avoid exploitatin via looking for .env files.

---

## Professional Experience

## Camelot.exchange

**Smart Contract Developer** | *Jan 2023 - Present*

- Developed and implemented **airdrop functionality** for xGRAIL users.
- Engineered internal protocol **plugins**, enhancing system flexibility and performance.
- Collaborated with cross-functional teams to integrate new features and maintain code quality.

## [KoiPond Launchpad](https://koipond.fi/)
- Designed and implemented smart contracts for **auction mechanisms**, **gauge staking**.
- Designed and implemented smart contracts for the Koi Launchpad platform, enabling new project launches and token sales in any ERC20 token.
- Developed key features including:
  - Tiered staking system for allocation priority
  - Vesting schedules for token distributions
  - Whitelist management and KYC integration
  - Dynamic pricing mechanisms for token sales
- Implemented security measures like access controls, rate limiting, and emergency pause functionality.
- Collaborated with frontend team to create intuitive interfaces for project creators and participants.
- Conducted code reviews and optimizations to ensure gas efficiency and contract security.
- Assisted in smart contract audits and addressed identified vulnerabilities.
- Created test ui for contracts, to allow users to test the contracts before the launch.

[View Koi Launchpad on Twitter](https://x.com/KoiLaunchpad)

## [Èquilibre Finance](https://equilibrefinance.com/)

- Contributed to the development of core smart contracts for Èquilibre Finance's decentralized exchange (DEX) V2/V3 Uniswap-like platform.
- Implemented and optimized key features including:
  - Concentrated liquidity pools for efficient capital utilization
  - Integration of V2/V3 pools-gauge contracts.
  - Adaptive fee mechanism to dynamically adjust trading fees based on market conditions
  - Voting and governance contracts for decentralized decision-making
  - Use of beacon proxys for pools/gauges.
  - Refactor of immutable contracts to upgradeable contracts, using transparent proxy pattern.
- Developed and maintained subgraphs for efficient data indexing and querying of on-chain events. Specially for pools/gauges api stats.
- Collaborated on the creation of a custom oracle solution for reliable token pricing on the Kava blockchain.
- Created airdrop functionality and distribution mechanisms.
- Implementation of veTokenomics, including contracts for token locking and voting escrow.
- Worked on cross-chain bridging solutions to enhance interoperability with other blockchain networks.
- Participated in code reviews, testing, and auditing processes to ensure contract security and reliability.
- Assisted in the development of frontend interfaces and API services to interact with the smart contracts, providing cache and api endpoints to interact with the blockchain for fast ui response.

## [Keller Finance](https://keller.finance/)

- Contributed to the development of core smart contracts for Keller Finance's decentralized exchange (DEX) V2/V3 Uniswap-like platform.
- Implemented and optimized key features including:
  - Concentrated liquidity pools for efficient capital utilization
  - Integration of V2/V3 pools-gauge contracts.
  - Adaptive fee mechanism to dynamically adjust trading fees based on market conditions
  - Voting and governance contracts for decentralized decision-making
  - Use of beacon proxys for pools/gauges.
  - Refactor of immutable contracts to upgradeable contracts, using transparent proxy pattern.
- Developed and maintained subgraphs for efficient data indexing and querying of on-chain events. Specially for pools/gauges api stats.
- Collaborated on the creation of a custom oracle solution for reliable token pricing on the Kava blockchain.
- Created airdrop functionality and distribution mechanisms.
- Implementation of veTokenomics, including contracts for token locking and voting escrow.
- Worked on cross-chain bridging solutions to enhance interoperability with other blockchain networks.
- Participated in code reviews, testing, and auditing processes to ensure contract security and reliability.
- Assisted in the development of frontend interfaces and API services to interact with the smart contracts, providing cache and api endpoints to interact with the blockchain for fast ui response.

## [Xexlabs](https://xexlabs.com/)

- Developed and implemented smart contracts for the XEX token and Xexadon NFT ecosystem.
- Engineered the Xexaverse Game Contracts, integrating XEX rewards with gamified mechanics.
- Designed and implemented the Xexadon staking system with scalable rewards and boost mechanics.
- Created the ELX Refinement system, a lottery-style token conversion mechanism with tiered risk categories.
- Developed the ELX Jackpot system for luck-based token distribution with emission halving mechanics.
- Implemented the ELX Staking system for earning protocol fees with time-based locking and boost multipliers.
- Engineered migration contracts for transitioning from multi-chain to Fantom Sonic, including snapshot and airdrop functionalities.
- Designed and implemented airdrop mechanisms for ELX token distribution to community members.
- Contributed to additional features such as whitelisted DEX, AMM implementations, and daily FTM claiming mechanisms.

Key Contributions:
- Implemented complex boost mechanics across multiple systems, enhancing user engagement and rewards. The app can be seen here: https://elx-app.xexadons.com/
- Designed flexible and upgradeable smart contract architectures to allow for future adjustments and improvements.
- Integrated random number generation for fair lottery-style mechanics while ensuring system security.
- Developed efficient snapshot and migration systems for seamless transition between blockchain networks.
- Implemented tiered reward systems and time-based locking mechanisms to incentivize long-term participation.

## [Camelot](https://camelot.finance/)

- Contributed to the development of xGrail plugins for Camelot's ecosystem.
- Designed and implemented airdrop contracts for token distribution.
- Participated in code refactoring efforts to improve contract efficiency and 
