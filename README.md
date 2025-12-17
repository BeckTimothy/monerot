# Monerot - Monero Tools

##### Small bash tools/scripts for managing and automating Monerod and Monero-Wallet-CLI


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
