<!-- Replace the URL below with your preferred aesthetic Tumblr/Giphy GIF image address -->
<img src="![Cyberpunk Banner](https://giphy.com)" alt="Banner" width="100%">

# Chitrangath
**Web3 & Blockchain Engineer | Smart Contract Developer**

<!-- Shields.io Badges for Contact -->
<p align="left">
  <a href="https://linkedin.com/in/your-profile" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:your-email@example.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://twitter.com/your-handle" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
  </a>
</p>

### 👨‍💻 About Me
I'm a Web3 developer building at the intersection of Blockchain Security, Smart Contract Architecture, Web3 Full-Stack Engineering. I focus on writing secure, gas-optimized smart contracts and integrating them with scalable frontends. Passionate about solving complex problems in the EVM ecosystem and Blockchain Security

### 🛠️ Languages & Tools
<!-- Skillicons.dev for uniform, clean icons. Just add or remove abbreviations in the 'i=' parameter -->
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=solidity,eth,js,ts,react,nextjs,tailwind,nodejs,git,linux&theme=dark" alt="My Skills" />
  </a>
</p>

### 🚀 Featured Projects

**TerraLink: Decentralized Real Estate Asset Management Protocol**
An omni-channel property tokenization protocol enabling trustless secondary market sales, escrow-backed private rentals, and fractional yield generation.
* **Architecture:** * Designed a strictly governed ERC-721 state machine (`PropertyState`) ensuring immutable state transitions between direct sales, private rentals, and fractionalized ownership. 
  * Engineered a highly optimized yield-distribution engine in `FractionalInvestment.sol`. By implementing a mathematically rigorous global accumulator (`_accIncomePerShare`) and local `_rewardDebt` mappings, the contract distributes fractional rental income with **O(1) time complexity**, entirely bypassing gas-heavy `for-loops` over investor arrays.
  * Secured capital flows using OpenZeppelin’s `ReentrancyGuard` and `SafeERC20` to prevent reentrancy attacks and gracefully handle non-standard ERC-20 (USDT) return values.
  * Built the client-side DApp using React, TailwindCSS, and Wagmi/RainbowKit for seamless multi-wallet abstraction, directly reading on-chain events (e.g., `PropertyRegistered`) to index and render live property states asynchronously.
* **Impact:** Deployed the full suite of modular contracts to the Sepolia testnet, successfully abstracting away centralized escrow via trustless deposit deductions and autonomous rental termination. Validated protocol invariants and edge-cases locally using a robust Foundry testing suite.


### 💼 Experience & Open Source
* Built expertise in smart contract security and automated testing (Foundry).
* Follow professional open-source practices: code reviews, PR lifecycle management, and detailed technical documentation.
* Currently exploring Zero-Knowledge Rollups, Security Audits and RWA

