# Jibra TestNet
Libra Testnet

~~~
git clone git@github.com:oboluscrypto/jibraTestnet.git
cd jibraTestnet
docker run -it --volume `pwd`/peers:/peers obolus/libra:client -a VALIDATOR_IP -p 30307 -s /peers/trusted_peers.config.toml
~~~
