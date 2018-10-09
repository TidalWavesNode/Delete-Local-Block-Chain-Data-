# Delete-Local-Block-Chain-Data (Automated script)

If the VPS gets stuck on a block, corrupted, or otherwise doesn't seem to be syncing or downloading new blocks this script Deletes local block chain data files and restarts the masternode.

## Usage

wget -q https://raw.githubusercontent.com/TidalWavesNode/Delete-Local-Block-Chain-Data-/master/DLBF.sh

bash DLBF.sh

Answer yes to the prompts


## Wait for the VPS to fully sync (compare blocks to Wagerr Explorer)

./wagerr-cli getinfo (will show current stats of syncing)

Start Local Control Wallet –

startmasternode alias false

Start VPS Masternode –

cd ~/wagerr-2.0.1/bin

./wagerr-cli startmasternode local false

# Donations
$WGR: WagerrLiVo87tYRpLmwV3QJvB2sY58hS5f
