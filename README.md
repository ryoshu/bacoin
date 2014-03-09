# Bacoin [BCN, ∬] Integration/Staging Tree
http://www.ryoshu.com/bacoin/

![Bacoin](http://www.ryoshu.com/wp-content/uploads/2014/03/1995_China_1oz_Gold_Pig_coin.jpg)

## What is Bacoin? - Delicious currency
Bacoin is like Litecoin, but based on Dogecoin, and also much more tasty.
http://www.ryoshu.com/bacoin/

## License - license
Bacoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions - developers
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

## Frequently Asked Questions

### How much bacoin can exist?
TBD

### How do I get bacoin?
Coin design has commenced.

### How do I build bacoind?

    sudo apt-get install build-essential \
                         libssl-dev \
                         libdb5.1++-dev \
                         libboost-all-dev \
                         libqrencode-dev \
                         libminiupnpc-dev

    cd src/
    make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### Ports
RPC TBD
P2P TBD
