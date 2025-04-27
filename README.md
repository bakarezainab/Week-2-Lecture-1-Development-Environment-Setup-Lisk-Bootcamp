# Week-2-Lecture-1-Development-Environment-Setup-Lisk-Bootcamp


## Contrast Between Hardhat And Foundry Environments Both When Building, Compiling And Deploying Smart Contracts
| Features            | Hardhat                     | Foundry    |
|--------------------|-----------------------|--------------------|
| Language         | JavaScript / TypeScript        | Rust (CLI) + Solidity    |
| Setup         | Node.js environment, requires npm install       | Lightweight binary installation via foundryup |
| Plugin Ecosystem       | Extensive      | Limited but growing      |
| Speed       | Moderate, especially with larger codebases    | Extremely fast due to Rust performance      |
| Scripting     | scripts/deploy.js/ts with ethers.js| forge script + broadcast      |
| Error Tracing     | Source maps, stack traces, decent debugging| Superior stack traces, foundry snapshots      |
| Gas Reporting     | Via plugin like hardhat-gas-reporter| Built-in by default (forge test --gas-report)      |
| Compilation     | Uses solc under the hood via plugins| Native, blazing-fast compiler (forge build)|
| Compilation Speed     | Moderate| Very fast (3-10x faster than Hardhat)      |
| Deployment     | JavaScript scripts| Forge script (using Solidity)      |







## Difference Of Building A Smart Contract Using Local IDE Environments Like Visual Studio Rather Than In Remix
	
| Features            | Local IDE (e.g., VS Code)                     | Remix IDE    |
|--------------------|-----------------------|--------------------|
| Setup Complexity         | Higher (requires local tooling installation)        | Needs internet access (mostly)    |
| Offline Usage         | Fully offline development possible       | Lightweight binary installation via foundryup |
| Git Integration       | Native      | Limited      |
| Debugging       | Advanced debugging tools    | Built-in debugger with visual interface      |
| Performance     | High for large projects| Can slow down with complex projects      |
| Dependencies Management     | Full package management| Limited dependency management      |
| Testing Support     | Full testing environments (Mocha, Foundry, etc.)| Limited to inline testing via Remix plugins      |
