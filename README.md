# UltimaCoin_Masternode
Scrypt for Ultima Masternode installation


```
wget https://raw.githubusercontent.com/Simo190/UltimaCoin_Masternode/master/install_MN_Ultima.sh && bash install_MN_Ultima.sh
```

Only copy this scrypt in your VPS.

The daemon start automatically!!!! 

## Desktop Wallet

1) In you debug consolle copy and paste this command:

  masternode genkey

  copy and use the answer when VPS ask your Private Key

2) In you debug consolle copy and paste this command:

  getaccountaddress MN1 (you can use MN1, MN2 and so on)

3) Send 1,000 ULT at previous address (MN1)

4) In you debug consolle copy and paste this command, you must wait for at least the beginning of the confirmations of the previous transaction :

  masternode outputs

5) go on menu tools and open Masternode Configuration File
  Compose your masternode's string like this
  
  MN1 YourIpAddress:8420 YourPrivateKey TxCollateralTransaction Outputs
  
6) Close your wallet and restart it

7) Start your Masternode in debug consolle:
  masternode start-alias MN1
  
  












