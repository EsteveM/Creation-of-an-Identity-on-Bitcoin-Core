# Creation of an Identity on Bitcoin Core

This project is intended to set up and use a blockchain identity by means of a bitcoin wallet.

## Table of Contents

* [Description of the Project](#description-of-the-project)
* [Getting Started](#getting-started)
* [Contributing](#contributing)

## Description of the Project

This project shows the generation of a blockchain identity. Using a wallet client, a new private-public key pair is generated, and a wallet address created. Then, a message, which includes the wallet address, is signed with the corresponding private key. Finally, the message signature is verified.

The following files have been included as part of this project:

* Project answers - Create your Identity on Bitcoin Core.md: This file contains wallet address, message, and message signature for this project.
* README.md: This is the documentation file that you are reading right now.

## Getting Started

The wallet client used is downloaded and then installed from [Electrum.org](https://electrum.org/#download). The message to be signed is then obtained from [this web application](https://bitcoin-message-validation.firebaseapp.com/) providing the wallet address. Finally, the wallet client is used to sign the message, and the web application to verify the signature.

Please, note that if you use the latest wallet client version from [Electrum.org](https://electrum.org/#download), your wallet should be installed as legacy. In this way, it works successfully with the [web application](https://bitcoin-message-validation.firebaseapp.com/). The reason is that the default receiving wallet addresses do not work with the web application if the wallet is defined as segwit.

## Contributing

This repository contains all the work that makes up the project. Individuals and I myself are encouraged to further improve this project. As a result, I will be more than happy to consider any pull requests.