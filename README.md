# SHA256
Fast and small JavaScript implementation of the SHA-256 hash function. License and copyright free.

Example use:

var hexString = SHA256.hash('text');

To get the hash value as a byte array, use:

var hashAsByteArray = SHA256.digest(messageByteArray);

The SHA256.hash() function returns a hex string and SHA256.digest() returns a byte array. If the message argument for SHA256.hash() or SHA256.digest() is a string it's converted to a UTF-8 byte array before the hash value is calculated.
