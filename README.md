# QamCoin-Blockchain-Explorer
Block explorer for QamCoin CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon QamCoind. It should be accessible from the Internet. Run QamCoind with open port as follows:
```bash
./QamCoind --enable-cors="*" --enable-blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=11888
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Development
Devs:
    @devopsralf

### Note

A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
