# Donation Leaderboard
This web-application allows the display of transactions to an address on the Ethereum blockchain as a leaderboard.

**Important:** We use branches to deploy separate leaderboards! The master is intended as a easy-to-fork template and currently looks like [this](https://placeholder-leaderboard.netlify.com).

## Status
Production ready!

**First instance deployed** - see [ScalingNOW!!! campaign](https://scalingnow.giveth.io)

**Second instance deployed** - see [Giveth Donation Leaderboard](https://leaderboard.giveth.io)

## Important
We use different branches to build out the leaderboard for different initiatives to **deploy directly from their branch**. If you are a contributor to a specific deploy please stay within that branch and don't commit back to *Master*.

### Primer
After the great success of the [Merry Merkle](https://merrymerkle.com) project by [TrueBit Team](https://truebit.io/) - they managed to collect over 130.000€ in ETH donations for a local charity project, we at [Giveth](https://giveth.io) figured it would be great if more Ethereum projects could use such a tool.

After playing with our fork a bit, we still decided to build our own tool, because we found the original project very specialized for its cause and we would love to make a tool that can be of general use for many other developers down the line.

## Contributors
This project is actively seeking contributions. If you are experienced with web3 and/or React, please don't hesitate to contact the repository owner @geleeroyale on GitHub or Riot.im

### Goal
The mission - should you accept it - is to build out a react leaderboard frontend and a web3 backend that can monitor an address for transactions. Please see the [Issue List](https://github.com/geleeroyale/eth-leaderboard/issues) for details on tasks.

### Installation

1 - Star, Fork and Clone the repository

2 - Go to your local repo directory and run ```npm install``` (requires [npm](https://www.npmjs.com/))

3 - Visit the **[Issue List](https://github.com/geleeroyale/eth-leaderboard/issues)** or the **[Planning Board](https://github.com/geleeroyale/eth-leaderboard#boards?repos=121978742)**

### Stack
  - Etherscan API (should be switched to open blockexplorer/scraper - see issues)
  - web3.js
  - glamor
  - Reactjs via ```create-react-app```

### React

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Below you will find some information on how to perform common tasks.<br>
You can find the most recent version of this guide [here](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md).

#### Attribution
Eth-Scaling graphic by @cleo
