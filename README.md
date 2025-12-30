# Monerot - Monero Tools

###### Lightweight bash tools/scripts for managing and automating Monerod and Monero-Wallet-CLI. These scripts assume monerod is running and monero-wallet-cli is in PATH. For those reason bash, monerod, and monero-wallet-cli are dependencies.

---
### autogen:

A bash script to generate 1 or n wallet subaddresses specified by -n flag and output to a file.


```
EXAMPLE: autogen -c 500 --output-file /home/admin/myWalletAddresses.txt -n ./moneroWalletFile -p Passw0rd

-h, --help: Show this help message
-c, Specify a count value (Default: 1)
-o, --output-file: Speficy a location and filename for the output, (Default: ./addresses.txt)
-n, --wallet-name: Specify the location and filename of a monero wallet file (**Required)
-p, --password: Specify the password for your monero wallet
```

---
### autosweep:

A bash script to sweep all monero from specified wallet to a specified address

WIP

---
### c3poolupdate

A bashscript to set c3pool payout threshold to minimum or specified value for the specified wallet

```
EXAMPLE: c3poolupdate -p 500 --wallet 8748cigrtHj9uB4voKKQd67PAG1crVAR4Y9G6Ku2s42UFx1RVbnDCBH7Dc9c8sYGvE5yhM5pniJNs86ki3hPk1wQDtePjRX

-h, --help: Show this help message
-w, --wallet: Specify the address of the payout wallet
-p, --pay-threshold: Specify the value the payout threshold should be set to 0.1 - 1000 (Default: 0.1)

---
### findWallets

 
---
### donateXMR


---
### donateWallet


---

