PearlBitcoin Source Code
================================

http://www.pearlbitcoin.org

Copyright (c) 2009-2018 Bitcoin Developers
Copyright (c) 2011-2018 PearlBitcoin Developers

What is PearlBitcoin?
----------------

PearlBitcoin is a lite version of Bitcoin using scrypt as a proof-of-work algorithm.
 - 2.5 minute block targets
 - Block halving	210000 blocks
 - 175000000 total coins

The rest is the same as Bitcoin.

 - 250 coins per block
 - RPC port	28928
 - P2P port	28927

For more information, as well as an immediately useable, binary version of
the PearlBitcoin client sofware, see http://www.pearlbitcoin.org.

License
-------

PearlBitcoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the PearlBitcoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/pearlbitcoin-project/pearlbitcoin/tags) are created
regularly to indicate new official, stable release versions of PearlBitcoin.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./pearlbitcoin-qt_test

NODE List

Peers - PearlBitcoin

addnode=1.22.111.14:53633
addnode=109.197.31.56:62929
addnode=14.102.40.242:59916
addnode=14.102.40.248:26329
addnode=150.129.80.242:50706
addnode=150.129.80.244:28927
addnode=180.254.111.69:49167
addnode=185.205.209.252:49406
addnode=188.35.131.157:58993
addnode=207.108.228.175:52476
addnode=212.73.150.254:53388
addnode=36.76.31.0:57084
addnode=37.97.242.80:28927
addnode=47.89.248.250:28927
addnode=51.15.162.24:28927
addnode=51.15.185.7:40130
addnode=65.189.242.120:50294
addnode=80.251.112.201:51183
addnode=82.147.93.32:49917
addnode=82.79.83.3:30012
addnode=85.214.205.196:28927
addnode=86.123.50.189:65290
addnode=94.156.144.211:52724
