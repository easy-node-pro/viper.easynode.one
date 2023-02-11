# Viper by Easy Node
We saw a lot of requests to easily break LP and swap funds so we fired up a site, the original app readme is below.  

## Status
[![Netlify Status](https://api.netlify.com/api/v1/badges/e85b1faf-8489-447e-8594-5306fbfb31dd/deploy-status)](https://app.netlify.com/sites/vipereasynode/deploys)

# Viper Frontend

## Development

### Prerequisites

1. [Git](https://git-scm.com/)
2. [NodeJS >=12 (>=16 recommended)](https://nodejs.org/en/)
3. [Yarn](https://yarnpkg.com)

### Installation

```bash
git clone https://github.com/VenomProtocol/frontend.git
cd frontend
yarn install
```

### Configuring the environment

Create a new file called .env.local in the root of the project folder.

#### Harmony / Viperswap

Add the following to the empty .env.local file:
```
REACT_APP_CHAIN_ID="1666600000"
REACT_APP_NETWORK_URL="https://api.harmony.one"
```

#### Binance Smart Chain (BSC) / Cobraswap

Add the following to the empty .env.local file:
```
REACT_APP_CHAIN_ID="56"
REACT_APP_NETWORK_URL="https://bsc-dataseed.binance.org/"
```

### Run

```bash
yarn start
```
