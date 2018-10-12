 # UltimaCoin_Masternode
 

## Desktop Wallet

1) In you debug consolle copy and paste this command:

             masternode genkey

  copy the ansewer, you will use it when VPS ask your Private Key

2) In you debug consolle copy and paste this command:

            getaccountaddress MN1 (you can use MN1, MN2 and so on)

3) Send 1,000 ULT at previous address (MN1)

4) In you debug consolle copy and paste this command, you must wait for at least the beginning of the confirmations of the previous transaction :

            masternode outputs (copy the answer you will use it when you will write the Masternode Configuration File)

5) Go on your VPS and post the scrypt below

6) go on menu tools and open Masternode Configuration File
  Compose your masternode's string like this
  
            MN1 YourIpAddress:8420 YourPrivateKey TxCollateralTransaction Outputs
  
7) Close your wallet and restart it

8) Start your Masternode in debug consolle:

            masternode start-alias MN1
  
  ## VPS


Scrypt for Ultima Masternode installation


```
wget https://raw.githubusercontent.com/Simo190/UltimaCoin_Masternode/master/install_MN_Ultima.sh && bash install_MN_Ultima.sh
```
Only copy this scrypt in your VPS.

The daemon start automatically!!!!












