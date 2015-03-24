# SHA256
Fast and small JavaScript implementation of the SHA-256 hash function. License and copyright free.

Example use:

var hexString = SHA256.hash('text');

The message parameter for SHA256.hash() is converted to a UTF-8 byte array.

To get the hash value for a byte array directly without any conversion, use:

var hashAsByteArray = SHA256.digest(messageByteArray);

The SHA256.hash() function returns a hex string and SHA256.digest() returns a byte array.
