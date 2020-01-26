# Open Exchange Protocol

The Open Exchange Protocol is a simple and powerful protocol built on top of the Open Assets Protocol. It allows issuance of a new coin called Skeleton Coin (SKN) and it's tranfer to facilitate exchange of blockchain currencies and assets. The Open Exchange Protocol is an evolution of the concept of the Open Assets Protocol.

* [Open Exchange Protocol specification](OEP-Spec.mediawiki): Specification of the core protocol

The following Open Assets Protocol reference documents are available:

* [Open Assets Protocol specification](specification.mediawiki): Specification of the core protocol
* [Open Assets Address Format specification](address-format.mediawiki): Special address format for wallets supporting the Open Assets Protocol, preventing assets from being sent to legacy wallets
* [Asset Definition Protocol specification](asset-definition-protocol.mediawiki): A protocol built on top of the Open Assets Protocol for associating an asset with metadata
* [Payment Requests specification](payment-requests.mediawiki): extensions to [BIP-70](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) and [BIP-21](https://github.com/bitcoin/bips/blob/master/bip-0021.mediawiki) describing payments in terms of assets instead of (or together with) regular bitcoins
* [Payment Methods specification](payment-methods.mediawiki): A protocol for negotiating the assets to be included in an [Open Assets Payment Request](payment-requests.mediawiki).

Source code related to the Open Assets Protocol:

* [`openassets` Python module](https://github.com/OpenAssets/openassets): The reference implementation of the Open Assets Protocol
* [Colorcore](https://github.com/OpenAssets/colorcore): A client providing a command line and RPC interface for performing operations through the Open Assets Protocol
* [NBitcoin](https://github.com/NicolasDorier/NBitcoin): A Complete .NET Library for Bitcoin with its [TransactionBuilder](http://www.codeproject.com/Articles/835098/NBitcoin-Build-Them-All) to issue, transfer and swap assets
* [BTCRuby](https://github.com/oleganza/btcruby): A Complete Ruby Library for Bitcoin with its [TransactionBuilder](https://github.com/oleganza/btcruby/blob/master/lib/btcruby/open_assets/asset_transaction_builder.rb) to issue, transfer and swap assets
* [CoreBitcoin](https://github.com/oleganza/CoreBitcoin): A Complete Objective-C Library for Bitcoin with support for [Payment Requests](payment-requests.mediawiki) and [Payment Methods](payment-methods.mediawiki)
* [openassets-ruby](https://github.com/haw-itn/openassets-ruby): A Ruby implementation of the Open Assets Protocol. This library is able to perform Open Assets operations using APIs like Colorcore.
