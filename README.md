# Creating my first Substrate chain
[Full tutorial](https://substrate.dev/docs/en/tutorials/create-your-first-substrate-chain/)
### Setting Up
#### Compiling the Node Template
It is required to complete the Official Installation guide. After `rustup` has been installed and configured, and you've configured the Rust toolchain to default to the latest stable version you can return to these steps.
```bash
cd substrate-node-template
# NOTE: you should always use the `--release` flag
cargo build --release
# ^^ this will take a while!
```
#### Compiling the Front-End Template
As the front-end template uses [ReactJS](https://reactjs.org/), [Node.js](https://nodejs.org/) and [Yarn](https://yarnpkg.com/) must be installed. If you don't have these tools, you can install them by following these instructions:
- [Install Node.js](https://nodejs.org/en/download/)
- [Install Yarn](https://yarnpkg.com/lang/en/docs/install/)
```bash
# Install the dependencies
cd substrate-front-end-template
yarn install
```
### Starting the Node & the Front-End
```bash
# Run a temporary node in development mode
./target/release/node-template --dev --tmp
```

```bash
# Make sure to run this command in the root directory of the Front-End Template
yarn start
```
