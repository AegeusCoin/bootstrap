![Aegeus Bootstrap](https://ipfs.io/ipfs/QmZnyYCh7TRNgN4wZBFiYPzbptiLCzAZckiV3nC1CRtqcK)

### Instructions

1. Download bootstrap.dat.gz <a href="https://github.com/AegeusCoin/bootstrap/raw/master/bootstrap.dat.gz">Here</a>

2. Place bootstrap.dat.gz inside of your Aegeus data directory and decompress it with your favorite software (gunzip for Linux/Mac, 7zip/winrar/winzip for Windows):
 - Windows: %APPDATA%\AEGEUS\
 - Linux: ~/.aegeus/
 - Mac: ~/Library/Application Support/AEGEUS

2(b). If this is a replacement for an already-running installation, be sure to remove the 'blocks' and 'chainstate' directory from the appropriate data directory listed above before starting up with the new bootstrap.dat.

3. Open your Aegeus wallet and the sync will begin reading blocks from the local bootstrap instead of net

Depending on which block the bootstrap left off at, some blocks may still need to be retrieved from peers.  We will keep this file as updated as possible to minimize the amount of time that might take.

