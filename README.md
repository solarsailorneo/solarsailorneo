# Solar Sailor
## :envelope: solarsailorneo@protonmail.com

## Purpose
To use the skills I have learned in my career to contribute to the development of AI and web3.

## Projects (Engineering: 8 years | Development: 5 years)

### DeductiveAI (Rust) <br /> [2023] (In progress)
- Developed an AI with different approach than transformers to eliminate the inductive nature of the process.
- Used specialized datastructure to accomplish deductive reasoning.
- Designing zero-knowledge proof system that involves natural language (in progress).

### AI to classify Documents (Rust, Python, React) <br /> [2023]
- Developed an AI-powered tool capable of categorizing PDF documents into distinct classes, featuring an online interface for personalized model training.
- Developed a rust backend to handle the classification of the trained model.
- Developed a python backend with flask and pytorch to train individual models.
- Developed a React frontend to direct the user to training or using the model.

### CustomGPT (Rust, React, Pytorch) <br /> [2023]
- Trained a custom AI using a GPT2 baseline for a chatbot.
- Made a react frontend for chatting with the AI.
- Made a rust backend that served the custom GPT2 model.
- Created an admin dashboard for testing and constructing supervised learning data.

### Filum Generative Art Project (React, P5.js, Solidity) [2022-2023] <br /> ([website](https://solarsailor.space/art) | [medium article](https://medium.com/@solarsailorneo/the-art-of-strings-knots-and-physics-a-journey-through-time-and-space-c986451220c3)
- Created art project with novel approach using fundamental physics of strings.
- Used ERC-721a contract with additional functionality for this specific project.
- Designed a website that showcases multiple dynamic pieces of art simultenously with low amount of resources.
- Deployed to Mainnet.

### ERC721a NFT Minter (ERC721a Contract and Frontend) [2022] <br /> ([website](https://optimizednftminter.netlify.app/) | [git](https://github.com/solarsailorneo/optimizedNFTMinter) | [workflow](https://github.com/solarsailorneo/optimizedNFTMinter/network) | [contract](https://goerli.etherscan.io/address/0xc920a9acb898621a1d951bc5ab5d9d81f183d5fb))
- Leveraged a ERC-721a contract to create an optimized NFT minter website.
- Connected Frontend with Hardhat and Remix to troubleshoot.
- Understood at a high level the optimizations done in the ERC721a contract.

### Digital Avatar Identity (ERC725Y Contract) [2022] <br /> ([git](https://github.com/solarsailorneo/digitalAvatarIdentity) | [workflow](https://github.com/solarsailorneo/digitalAvatarIdentity/network))
- Built a smart contract with a key that can store multiple retrievable attributes on-chain.
- Built tests in hardhat and mocha to verify functionality of contract.

### Multi Token Standard (ERC1155 Contract) [2022] <br /> ([git](https://github.com/solarsailorneo/mulitTokenStandard) | [workflow](https://github.com/solarsailorneo/mulitTokenStandard/network))
- Built a smart contract that inherited from the ERC1155 standard.
- Designed constructor so that a number of tokens can be set when deploying the contract.
- Built test in hardhat and mocha to verify that the number of tokens were minted to the deployer wallet.

### NFT Minter (ERC721-Based Contract and Frontend) [2022] <br /> ([website](https://snazzy-horse-8858d0.netlify.app/) | [git](https://github.com/solarsailorneo/minterNFT) | [workflow](https://github.com/solarsailorneo/minterNFT/network) | [contract](https://rinkeby.etherscan.io/address/0xdebe8510ecb716408513c90a454416dc6dc79869))
- Built a react frontend to mint NFTs.
- Built and deployed an NFT-minter contract in the Rinkeby testnet.

### TestCoin (ERC20 Contract) [2022] <br /> ([git](https://github.com/solarsailorneo/testCoinICO) | [workflow](https://github.com/solarsailorneo/testCoinICO/network) | [contract](https://rinkeby.etherscan.io/token/0xCabfb905163A197931a88CBc226ea230007333Dc))
- Built and deployed a smart contract for a test coin in the Rinkeby testnet.
- Created a liquidity pool for TestCoin in Uniswap.

### Shared Wallet (Contract) [2022] <br /> ([git](https://github.com/solarsailorneo/sharedWallet) | [workflow](https://github.com/solarsailorneo/sharedWallet/network))
- Built a wallet that has an owner who can set allowances for other wallets.
- Used modifier functionality to contain pre-function conditions.

### Token Crowdsale (Contract) [2022] <br /> ([git](https://github.com/solarsailorneo/tokenCrowdsale) | [workflow](https://github.com/solarsailorneo/tokenCrowdsale/network))
- Built a custom token that can be initially sold to a group of people.
- Reentrancy-guard was used to prevent hacking of the crowdsale.
- Used truffle deployment and chai tests to verify functionality.

### Venetian Election DAO (Frontend and Backend) [2022] <br /> ([website](https://darling-nasturtium-65b4bd.netlify.app/) | [git](https://github.com/solarsailorneo/venetianElectionDAO) | [workflow](https://github.com/solarsailorneo/venetianElectionDAO/network))
- Designed a DAO wallet-election system based on the venetian election process (random/election rounds).
- Built a react frontend for the designed election system leveraging a Moralis github repository.
- Built a nodejs backend to compute the selection process.
- Maintained my git repository with clean and coherent versioning, tags, commits, branches, and merging (copied repo to kill the trace. Ask for a screen share if want to see).

### NFT Transaction Tracker (Frontend) [2022] <br /> ([website](https://vermillion-sfogliatella-6b7bdb.netlify.app/) | [git](https://github.com/solarsailorneo/eventDetectorNFT) | [workflow](https://github.com/solarsailorneo/eventDetectorNFT/network))
- Built a react front-end with NFT contract input field to track transfers.

### NFT cross-asset Model [2021-present]
- Built a power-law model that used population proxies and community strength in order to arrive at NFT “fair” valuations [Excel].
- Extrapolated and verified the model with other asset classes like Bitcoin, Ethereum, US houses, and gold.
- Built a demographic model in order to verify and bound the value-prediction of NFTs to remain under what is humanly possible [Excel].

### Bitcoin Trading Algorithm [2019-2020]
- Built an algorithm based on price and volume that would automatically buy and sell Bitcoin through Robinhood [python, Robinhood API].

### S&P500 Machine Learning Model [2019]
- Built a machine learning model to classify whether the S&P would go up or down based on price, volume, and volatility historical time series [python, pytorch library].
- Made visual 3d plots to analyze price, volume, and volatility asset profiles to understand how the data works from a human perspective [python, pandas library].

### Lidar Security System (Pointcloud Clustering and Machine Learning) [2019-2022]
- Designed and implemented a data-processing pipeline in order to label 5000 pointclouds per day for machine learning training [C++, bash].
- Implemented various custom neural networks to classify our data in real-time in a jetson-xavier NX platform. Initial classification performance was 10 Hz. Improved performance to 40 Hz [python, pytorch, C++, CUDA, TensorRT].

### 5-degree-of-freedom Robotic Arm [2018-present]
- Designed a Multi-input Multi-output controller algorithm for a 5 degree-of-freedom manipulator (6 linked bodies). [C++]
- Multithreaded and modified pointcloud registration algorithm resulting in a 6X performance improvement. [C++]
- Massively parallelized pointcloud registration algorithm. [CUDA]
- Derived the math and implemented forward and inverse kinematics of 6 linked bodies. [C++]
- Derived and implemented first order dynamics (inertia, gravity, and centripetal coriolis) of manipulator. [C++]

### Team Management for Isaac SDK [2019]
- Managed a team of two engineers whose job was to incorporate our existing code into the Isaac library framework [C++, Isaac Library].
- Scheduled project milestone meetings which were to the point and efficient.
- Helped the engineers with tasks whenever they needed me to step in.


### Skills
- C++ (8.5/10)
- Rust (8.0/10)
- Python (8.0/10)
- Pytorch (9.0/10)
- Solidity (7.5/10)
- Hardhat, Truffle, Chai (7.0/10)	 
- ReactJS (8.5/10)      
- Node (7.0/10)
- Git (9.0/10)
- Data Analytics (10.0/10)
- Linux (8.7/10)

