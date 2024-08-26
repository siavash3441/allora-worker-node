
## Requirements


- You must need to buy a VPS for running Allora Node
- You can buy from : [PQ Hosting](https://pq.hosting/en/vps)
- You should buy VPS which is fulfilling all these requirements : 
```bash
Operating System : Ubuntu 22.04
CPU : Minimum of 1/2 core
RAM : 2 to 4 GB
Storage : SSD or NVMe with at least 5GB of space
```
## Create Wallet & Request Faucet

- Install : [Keplr Extension](https://chrome.google.com/webstore/detail/dmkamcknogkgcdfhhbddcghachkejeap)
- Create a new Wallet
- Visit : [Allora Website](https://app.allora.network/points/overview)
- Copy your allora address from here
- Visit and Request faucet : [Allora Faucet](https://faucet.testnet-1.testnet.allora.network/)
- If there is an error, try 3-5 times

## Deployment

- Open termius/putty terminal
- Paste these 2 commands one by one
```bash
rm -rf allora.sh allora-chain/ basic-coin-prediction-node/
```
```bash
wget https://raw.githubusercontent.com/siavash3441/allora-worker-node/main/allora.sh && chmod +x allora.sh && ./allora.sh
```
- Atlast you will see some logs like this :


- It means your node is running

## update
If it is not updated, change the following file

```bash
docker rm $(docker ps -a -q) --force
docker rmi $(docker images -a -q) --force
```

```bash
nano model.py
```

Change intervals to

```bash
intervals = ["10m", "20m", "1h", "1d"]
```
