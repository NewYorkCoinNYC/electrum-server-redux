Electrum-server for the newyorkcoin Electrum client
=========================================

  * Author: CryptoLover705
  * Language: Python

Features
--------

  * The server indexes UTXOs by address, in a Patricia tree structure
    described by Alan Reiner (see the 'ultimate blockchain
    compression' thread in the Bitcointalk forum)

  * The server requires newyorkcoind, leveldb, and plyvel

  * The server code is open source. Anyone can run a server, removing
    single points of failure concerns.

Installation
------------

  1. To install and run a server, see INSTALL. For greater
     detail on the installation process, see [HOWTO.md](/HOWTO.md).

  2. To start and stop the server, use the 'electrum-server' script


License
-------

Electrum-server is made available under the terms of the MIT License.
See the included `LICENSE` for more details.
