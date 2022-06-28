NOD

--wallet-address=dero1qykrudlwkcrf79n69jv60u9ctld4ur8vglmk8gh5franh5aweaw6uqgjaf7ts --daemon-rpc-address 140.238.11.36:10100


# derod

auto arm

#!/bin/bash
sudo -i

screen

wget https://github.com/Zeusyf/derod/releases/download/beta/deroarm64.tar.gz
tar -xvf deroarm64.tar.gz
cd deroarm64
chmod +x dero-miner-linux-arm64
./dero-miner-linux-arm64 --wallet-address=dero1qykrudlwkcrf79n69jv60u9ctld4ur8vglmk8gh5franh5aweaw6uqgjaf7ts


