# chains

The Lux D-Chain (the DEX matcher) and F-Chain (the coordination plane for
confidential compute) in C++, each built behind `lux-cpp/node`'s VM seam.

`luxfi/dex` and `luxfi/fhe` are the protocols in Go; these are ports, and a
port that disagrees with the Go answer is wrong, not a variant. Every
primitive is reused from `lux-private/crypto` rather than carried here, so
there is one implementation of each hash in the tree.
