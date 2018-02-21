# gallion-Explorateur de blockchain

Explorateur de blocs pour Gallion

#### Installation

1) Il prend des données du démon Gallion. Il devrait être accessible depuis Internet. Exécutez gallion avec le port ouvert comme suit:
```bash
./gallion --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=3724
```
2) Il suffit de le télécharger sur votre serveur Web et modifier la variable 'API' dans config.js pour pointer vers votre démon.
