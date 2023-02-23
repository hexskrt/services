# 🤝 Games Of Alliance (Terra)

<figure><img src="../../../.gitbook/assets/ordos.png" alt=""><figcaption></figcaption></figure>

**Network:** Testnet | **Chain ID:** ordos-1 | **Version:** v0.1.0-goa

{% hint style="info" %}
Alliance is an open-source Cosmos SDK module that leverages interchain staking to form economic alliances among blockchains. By boosting the economic activity across Cosmos chains through creating bilateral, mutually beneficial alliances, Alliance aims to give rise to a new wave of innovation, user adoption, and cross-chain collaboration.
{% endhint %}

#### **Explorers** : [explorer.sxlzptprjkt.xyz/goa-ordos](https://explorer.sxlzptprjkt.xyz/goa-ordos)

#### **Public Endpoints**

* RPC : [rpc-goa-ordos.sxlzptprjkt.xyz](https://rpc-goa-ordos.sxlzptprjkt.xyz)
* API : [api-goa-ordos.sxlzptprjkt.xyz](https://api-goa-ordos.sxlzptprjkt.xyz)
* gRPC : `https://grpc-goa-ordos.sxlzptprjkt.xyz:443`

#### **State Sync Peer**
```
3f636d4bc99a309797bbaef5934fc9c3b8f3070c@146.190.81.135:01656
```

#### **Addrbook**
```
curl -Ls https://raw.githubusercontent.com/sxlzptprjkt/resource/master/testnet/goa/ordos/addrbook.json > $HOME/.ordos/config/addrbook.json
```

#### **Genesis**
```
curl -Ls https://raw.githubusercontent.com/sxlzptprjkt/resource/master/testnet/goa/ordos/genesis.json > $HOME/.ordos/config/genesis.json
```

#### **Live Peers**
```
PEERS="49d39420c03ec57240793bca9c8bcc4d339e976b@65.21.135.86:2000,6ebf0000ee85ff987f1d9de3223d605745736ca9@35.168.16.221:41356,2c66624a7bbecd94e8be4005d0ece19ce284d7c3@54.196.186.174:41356,418a1b8485e79d7e12f934ce7ec622cfcbde97d3@52.91.39.40:41356,8c3459aebbd9d74f213b65ad106641480b817ba4@38.242.134.77:10656,97b1ca0d0746126b2e2df45509c0e567af2facca@65.109.117.208:4000,2431611330c0cc60146a47ae89f3dd1c59c63f51@54.224.89.241:46656,3f486d41a9be9808ae60573712dbe7f6343eed31@164.92.91.248:10656,4ae10e9c2aac86c12da8ad585dd8ab7cab416ac6@89.163.130.46:26656,1677dabde46280cf7101472ac96777d855c0fbf0@65.109.32.226:26656,6deac387b71a1a83ce6ca3a7b3422ca472d19788@217.76.59.213:26656,74c67144a1dd53a73edff2bde17c0f42a025c924@65.21.134.202:27656,0c795b273ca8fbabe9421396129209ffe9d278b8@54.202.211.7:26656,c4c71cf90ebe51a215c71f5cc769cf7b188ff155@131.153.158.173:26656,2cae9adec56ffc7cb7447ddbd37adf4eba5525e8@65.109.93.35:29656"
sed -i -e "s|^persistent_peers *=.*|persistent_peers = \"$PEERS\"|" $HOME/.ordos/config/config.toml
```
