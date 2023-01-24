# Knowledge Sharing Program Based on Blockchain

This project is to build a Knowledge sharing platform in the blockchain.

## An example for using this project

### Project environment
You need to use this project in Unix computer (e.g. Linux, MacOS). This project test in the Ubuntu system. You can use the following command to install the required environment.(include: CMake,pkg-config,OpenSSL,Git,Rust)
```bash
curl https://getsubstrate.io -sSf | bash -s -- --fast
```

The codebase is installed using [git](https://git-scm.com/) and [yarn](https://yarnpkg.com/). This tutorial assumes you have installed yarn globally prior to installing it within the subdirectories. For the most recent version and how to install yarn, please refer to [Yarn](https://yarnpkg.com/) documentation and installation guides.

### Installation
```bash
# Clone the repository
git clone https://git.jackyu.cn/rust/Blog-Chain-App.git
```
### Compile the node
```bash
cd Block-Chain-App-Rust
cargo build --release
```
### Start the node
```bash
./target/release/node-template --dev
```
### Start the frontend
Open a new shell
```bash
cd frontend
```
If you are first time to start this frontend, you need to install yarn
```bash
yarn install
```
Now you can start the frontend to connect to a locally running node.
```bash
Yarn start
```

