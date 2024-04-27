# Which two statements regarding key rotation in OCI Vault are true?

> Each vault master encryption key is automatically assigned a key version. When you rotate a key, the Vault service generates a new key version. Cryptographic operations involving objects that were encrypted with the previous version of this key will continue to use the older key version. You can re-encrypt those objects with the current key version if you prefer.

- [x] Customers can rotate their keys by creating a new key version.
- [ ] Customers can only have OCI rotate their keys once a year.
- [ ] You cannot re-encrypt previously encrypted objects with a newly rotated key version.
- [x] Cryptographic operations involving objects that were encrypted with the previous version of a key will continue to use the older key version.
- [ ] Customers can rotate their keys every 30 days. They can also enter a service request (SR) to request a rotation sooner than 30 days since the last rotation.