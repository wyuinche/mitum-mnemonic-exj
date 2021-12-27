# mitum-mnemonic-exj

This is the example to generate mnemonic and mitum Keypair with or without seed.

This example use ether private key as seed and you should know that seed length for mitum keypair must be 32byte(256bit).

## Prerequisite

This project developed with,

* openjdk v16.0.1
* javac v16.0.1
* gradle v7.1.1

And the packages below must be installed.

* mitum-java-util v1.2.2
* org.web3j.crypto v5.0.0

## Examples

[example file](app/src/main/java/org/mitumc/mnemonicexj/App.java)

* Generate keypair without seed
See `generateMitumKeypairWithoutSeed()`

* Generate keypair with ether keypair
See `generateMitumKeypairFromEtherKey(String key)`