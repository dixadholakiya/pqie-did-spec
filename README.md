# did:pqie DID Method Specification

**Live spec:** https://dixadholakiya.github.io/pqie-did-spec/  
**JSON-LD Context:** https://dixadholakiya.github.io/pqie-did-spec/context.jsonld  
**W3C Registry PR:** https://github.com/w3c/did-extensions/pull/667

## About

The `did:pqie` method implements a Post-Quantum Identity Encryption DID method using Ring-LWE lattice cryptography (Kyber-1024 compatible), dual SHA-3-512/Blake2b identifier generation, and Hyperledger Indy + IPFS storage.

## DID Format

```
did:pqie:<sha3-512-8chars>:<blake2b-8chars>:<random-8chars>

Example: did:pqie:5135e697:8b7ecf94:a3f21bc0
```

## License

W3C Software and Document License

## Contact

**Maintainer:** dixadholakiya@gmail.com  
