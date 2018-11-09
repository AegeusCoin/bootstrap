![Aegeus Bootstrap](http://ipfsgw1.aegeus.io/QmZnyYCh7TRNgN4wZBFiYPzbptiLCzAZckiV3nC1CRtqcK)

### Instructions

1. Download QmTKM3LKJndwwvS6Aprc5Ptkz9DGy6PTSErJagqBmTfXw7 (aegeus-bootstrap.tar.gz) <a href="http://ipfsgw1.aegeus.io/QmTKM3LKJndwwvS6Aprc5Ptkz9DGy6PTSErJagqBmTfXw7">Here</a>

2. Place QmTKM3LKJndwwvS6Aprc5Ptkz9DGy6PTSErJagqBmTfXw7 inside of your Aegeus data directory and decompress it with your favorite software (gunzip for Linux/Mac, 7zip/winrar/winzip for Windows):
 - Windows: %APPDATA%\AEGEUS\
 - Linux: ~/.aegeus/
 - Mac: ~/Library/Application Support/AEGEUS

2(b). If this is a replacement for an already-running installation, be sure to remove the 'blocks' and 'chainstate' directory from the appropriate data directory listed above.

### A few details to cover
- If prompted to overwrite any existing files within the 'blocks' and 'chainstate' directory, choose yes.
- This file is hosted on the IPFS network.  If you already have IPFS installed, you can simply type: ipfs get QmTKM3LKJndwwvS6Aprc5Ptkz9DGy6PTSErJagqBmTfXw7
- This update includes up to block 384768 and unlike a typical bootstrap, will be much quicker.
- The filename will be QmTKM3LKJndwwvS6Aprc5Ptkz9DGy6PTSErJagqBmTfXw7 but will decompress and 'blocks' and 'chainstate' will extract

3. Open your Aegeus wallet and the sync will then check with peers for the best height and begin syncing to catch up.

We will keep this file as updated as possible to minimize the amount of time that might take.
