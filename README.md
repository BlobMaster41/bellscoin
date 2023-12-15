# Bells [BEL]
https://belscan.io/

Scrypt Proof of Work

#This branch contains the latest version 0.7.0 of the bells network.

![DogeCoin](http://static.tumblr.com/ppdj5y9/Ae9mxmxtp/300coin.png)

## What is Bells? - Such coin
Bells is the twin of DogeCoin, born before it, and just seen the lights now.

## License - Much license
DogeCoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions - omg developers
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

## Very Much Frequently Asked Questions

### How much doge can exist?
Total of 500,000,000 coins, special rewards system.

### How get $bel?
Scrypt Proof of Work

1 Minute Block Targets, 4 Hour Diff Readjustments

50% chance of 50 coins
20% chance of 100 coins
14% chance of 250 coins
10% chance of 500 coins
5% chance of 1000 coins
1% chance of 10000 coins

Halving at 129600 (~90 days)
Decreasing by 4/5ths at 259200 blocks (~180 days)
After block 518,400 (~1 year), reward of 2 coins.

### Wow make bellsd!
sudo apt-get install build-essential \
                     libssl-dev \
                     libdb5.1++-dev \
                     libboost-all-dev \
                     libqrencode-dev \
                     libminiupnpc-dev

cd src/
make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### RPC Ports
RPC 19918
P2P 19919

## Change Log
### 0.7.0
- Updated to protocol 70001
- Added peer seeding