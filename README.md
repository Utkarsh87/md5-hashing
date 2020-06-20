# MD5-Hash-Algorithm
Implement the MD5 hashing algorithm in Python following from the [original paper](https://tools.ietf.org/html/rfc1321)

Although it must be noted that MD5 algorithm has been proven to be an unsafe hashing/message digest algorithm, and hash collisions can be easily affected. Even salting along with MD5 isn't a good idea because the hashes can be calculated very quickly and hence hash collisions can be brute forced.
Hence using MD5 for password hashing, etc. is ill-advised.
MD5 though can be used for verifying data integrity(not authenticity) using checksums due to its high computation speeds.
