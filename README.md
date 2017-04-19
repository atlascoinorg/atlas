 

Atlas integration/staging tree
================================

http://www.atlascoin.org

Copyright (c) 2011-2017 Atlas Developers
Copyright (c) 2009-2017 Bitcoin Developers

----------------
The Atlas Cryptocurrency was created to provide financial freedom, safety, anonymity,  protecting privacy, for a better future for all the inhabitants of the earth and for offer to charitable causes and organizations.

Economic freedom.
Everyone can produce the Atlas Cryptocurrency need to use a computer or specialized electronic systems, that’s call miners.

Global – World without borders.
Use the Atlas Cryptocurrency for transactions between individuals or businesses on a global basis without borders.

Anonymity.
The Atlas Cryptocurrency is your electronic wallet and use anonymous without a need for any banking institution.

Safety and secure.
The cryptocurrency a can not be forged and és not controlled by banks and governments.  The Atlas Cryptocurrency is based on the bitcoin technology with the only difference that it uses the formula algorithm scrypt borrowed from the famous LiteCoin.

Peer to Peer.
With the Atlas Cryptocurrency the payments go directly to the individual or business, removing the need for a bank or building society.


Coin Properties

Algorithm
Scrypt
Type
PoW
Coin name
Atlas
Coin abbreviation
ATLAS
Address letter
L
RPC port
9068
P2P port
9067
Block reward
250 coins
Block halving
475000 blocks
Total coin supply
250000000 coins
Premine percent
5% 
Premine amount
12500000 coins
5% premine for bounties, giveaways, development, support and maintenance, new feature developments etc.


Advanced Properties

Coinbase maturity
20 blocks
Target spacing
5 minutes
Target timespan
60 minutes
Transaction confirmations
6 blocks

Seednode 1

45.55.83.96

For more information, as well as an immediately useable, binary version of
the Atlas client software, see http://www.atlascoin.org.

License
-------

Atlas is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Atlas
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/atlascoinorg/atlas/tags) are created
regularly to indicate new official, stable release versions of Atlas.

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
    ./atlas-qt_test


