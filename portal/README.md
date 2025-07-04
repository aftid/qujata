## Description
This is a `Post Quantum Cryptography` tool,
<br/>
using [React](https://github.com/facebook/create-react-app) framework.


## Pre-requisite
[Node.js](#https://nodejs.org/en/download) (includes npm) has to be installed on your system in order to run this project.

## Installation

1. To start, clone the qujata repository:
```bash
git clone https://github.com/atisorg/qujata.git
cd qujata/portal
```
2. Install yarn:
```bash
npm install -g yarn
```
2. Install dependencies and compile the application:
```bash
yarn install
yarn run build
```
3. Start the application (using  [api server](#https://github.com/atisorg/qujata/tree/main/api)):
```bash
yarn run start:quantum-api
```

4. Open your browser: `http://localhost:2001`


### Optional - working with mock server
under `qujata/portal` folder, run the following:

```bash
cd mock-server 
yarn install
yarn serve # if the command fails, run `yarn run-server` to start
```


