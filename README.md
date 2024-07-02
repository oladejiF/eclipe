# eclipe
REMEMBER, THIS IS ONLY FOR EDUCATIONAL PURPOSES! NOTHING IS PROMISED!
Amount Raised
Eclipse raised a total of $65M HackVC, Polychain Capital among other Investors image

Gettings Started
Installing Perequisite
sudo apt update
sudo apt upgrade -y
Install Rust
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
Reply with 1 image

Environment Variable
. "$HOME/.cargo/env"
image

check RUST version
rustc --version
Install Solana CLI
sh -c "$(curl -sSfL https://release.solana.com/stable/install)"
image

export PATH="/root/.local/share/solana/install/active_release/bin:$PATH"
image

check version if installed properly
solana --version
image

Install dependencies
Reply with y and proceed

sudo apt-get update
sudo apt-get install nodejs
sudo apt-get install npm
npm install --global yarn

Checking version
node -v
npm --version
yarn --version
image

Install Anchor
cargo install --git https://github.com/project-serum/anchor anchor-cli --locked
image

Check version
anchor --version
Create a Solana Wallet
solana-keygen new -o /path-to-wallet/my-wallet.json
image

Press ENTER ans save the Info image

Update configuration to use new wallet
solana config set --url https://testnet.dev2.eclipsenetwork.xyz/
image

solana config set --keypair /path-to-wallet/my-wallet.json

Save Solana address
solana address
