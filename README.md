# boxy-bootstrap
The latest BOXY Coin Blockchain Bootstrap

## Jan 30.2019 - https://bootstrap.boxyco.in/bootstrap.dat

## What is a blockchain bootstrap?
A bootstrap is a quick way to get your wallet synced to the blockchain. Generally, downloading and applying a bootstrap file is faster than downloading the blockchain from BOXY network peers.

## Installation on Windows
1. Stop your BOXY wallet by clicking "File" and then "Exit".
2. Navigate to BOXY wallet resource folder using Finder. Generally in C:\Users\<User-Name\AppData\Roaming\Boxy\
3. Delete all files except boxy.conf and wallet.dat
4. Download the Bootstrap and move to the BOXY resource folder. - https://bootstrap.boxyco.in/bootstrap.dat
5. Start your BOXY wallet.
6. The BOXY wallet will do the rest.

## Installation on Max OSX
1. Stop your BOXY wallet by clicking "BOXY-qt" and then "Quit" from the top menu bar.
2. Navigate to BOXY wallet resource folder using Finder. Generally in /Users/<User-Name>/Library/Application Support/Boxy/
3. Delete all files except boxy.conf and wallet.dat
4. Download the Bootstrap and move to the BOXY resource folder. - https://bootstrap.boxyco.in/bootstrap.dat
5. Start your BOXY wallet.

## Ubuntu command-line installation
1. Stop your BOXY wallet
   ```
   boxyd stop
   ```
2. Navigate to BOXY wallet resource folder. Generally in ~/.boxy/
   ```
   cd ~/.boxy/
   ```
3. Delete all files except boxy.conf and wallet.dat
   ```
   cp boxy.conf ~ && cp wallet.dat ~
   rm -ra .
   cp ~/boxy.conf . && cp ~/wallet.day .
   ```
4. Use wget to download the bootstrap
   ```
   wget https://bootstrap.boxyco.in/bootstrap.dat
   ```
5. Start your BOXY wallet (daemon)
   ```
   boxyd -daemon
   ```
