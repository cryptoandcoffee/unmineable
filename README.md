# Unmineable on Docker

Mine your favorite crypto coin with one command line.

```
docker run cryptoandcoffee/unmineable --coin=ETH --wallet=YOUR_WALLET_ADDRESS
```

Check your mining balance: https://unmineable.com/coins/CAKE/address/YOUR_WALLET_ADDRESS

## Don't have a wallet?

Create one https://metamask.io/


## Install docker

You need Docker to use this project.

https://docs.docker.com/get-docker/


## Supported coins

[https://unMineable/coins](https://unmineable.com/coins/)


## Options

```
CPU crypto miner.

Usage:
docker run cryptoandcoffee/unmineable --coin=CAKE --wallet=YOUR_WALLET_ADDRESS
options:
-c/--coin            The coin to be mined.
                     Check available coins here: https://unmineable.com/coins
-w/--wallet          Your wallet address.
-n/--worker-name     Worker name.

```

 
