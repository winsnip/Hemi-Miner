# Hemi CLI PoP Miner

![s1](https://github.com/user-attachments/assets/488a8719-7f5e-4813-9f14-213403bd5d02)

### 1. Install

```
bash <(curl -s https://file.winsnip.xyz/file/uploads/hami-miner.sh)
```

![s2](https://github.com/user-attachments/assets/563e4cac-9f86-4dae-8d50-3782aa59c91e)

### 2. Backup Data Wallet, Private Key, Pubkey Hash Dll

```
cat ~/popm-address.json
```
### 3. Claim Faucet

- Join Discord : https://discord.gg/hemixyz
- Got To Server Faucet Click /faucet Your-EVM-Wallet
- Claim Faucet tBTC On Discord or Web : https://coinfaucet.eu/en/btc-testnet/
- Use Pubkey Hash Address
- Done

![binance 1](https://github.com/user-attachments/assets/622da40a-a323-4a1d-806d-8807b7c7e75f)

### 4. Restart Node and Check Log

```
#check log
sudo journalctl -u heminetwork -f
```

```
#restart node
sudo systemctl restart heminetwork
```

![AIRDROP TAP TAP (1)](https://github.com/user-attachments/assets/17fefea3-9872-41eb-8e7e-9a049090f773)

### 5. Check Explorer

- Open : https://pop-miner.hemi.xyz/fund
- Paste Private Key
- Done and See

### 6. Delete Node (Optional)

```
sudo systemctl stop heminetwork && \
sudo systemctl disable heminetwork && \
sudo rm /etc/systemd/system/heminetwork.service && \
sudo systemctl daemon-reload
```

Source Official : https://docs.hemi.xyz/how-to-tutorials/tutorials/setup-part-1
