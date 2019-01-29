# boxy-bootstrap
The latest BOXY Coin Blockchain Bootstrap

## Jan 30.2019 - https://www.bootstrap.boxyco.in/bootstrap.dat

## Installation on Windows
1. Stop your BOXY wallet by navigating to clicking "File" and then "Exit" from the top menu.
2. Navigate to BOXY wallet resource folder using Finder. Generally in C:\Users\<User-Name\AppData\Roaming\Boxy\
3. Delete all files except boxy.conf and wallet.dat
4. Download the Bootstrap and move to the BOXY resource folder. - https://www.bootstrap.boxyco.in/bootstrap.dat
5. Start your BOXY wallet.

## Installation on Max OSX
1. Stop your BOXY wallet by navigating to clicking "BOXY-qt" and then "Quit" from the top menu bar.
2. Navigate to BOXY wallet resource folder using Finder. Generally in /Users/<User-Name>/Library/Application Support/Boxy/
3. Delete all files except boxy.conf and wallet.dat
4. Download the Bootstrap and move to the BOXY resource folder. - https://www.bootstrap.boxyco.in/bootstrap.dat
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
   wget https://www.bootstrap.boxyco.in/bootstrap.dat
   ```
5. Start your BOXY wallet (daemon)
   ```
   boxyd -daemon
   ```
