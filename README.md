Dazcoin 2.0.3

Bloody Dev want me to at Grey Paper here!!! Geeze!!!

Dazcoin is an experiment to see if a Troll can create a digital asset with help from community's that were Trolled

===========

What is Dazcoin?
--------------

[Dazcoin](https://Dazcoin.org/) is an implementation of the "Zerocash" protocol.
Based on Bitcoin's code, it intends to offer a far higher standard of privacy
through a sophisticated zero-knowledge proving scheme that preserves
confidentiality of transaction metadata. Technical details are available
in our [Protocol Specification](https://github.com/zcash/zips/raw/master/protocol/protocol.pdf).

This software is the Dazcoin client. It downloads and stores the entire history
of Dazcoin transactions; depending on the speed of your computer and network
connection, the synchronization process could take a day or more once the
blockchain has reached a significant size.




**Dazcoin is experimental and a work-in-progress.** Use at your own risk.






### Building

Build Dazcoin along with most dependencies from source by running:


 Get dependencies
```{r, engine='bash'}
sudo apt-get install \
build-essential pkg-config libc6-dev m4 g++-multilib \
autoconf libtool ncurses-dev unzip git python python-zmq \
zlib1g-dev wget curl bsdmainutils automake
```

 Install
```{r, engine='bash'}
# Build
./zcutil/build.sh -j$(nproc)
# fetch key
./zcutil/fetch-params.sh
# Run
./src/dazcoind
```

Currently only Linux is officially supported.

License
-------

For license information see the file [COPYING](COPYING).
