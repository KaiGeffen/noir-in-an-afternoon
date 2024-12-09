# Learn Noir in an afternoon (or get your money back[^fn])

## Useful install links

[Noirup](https://noir-lang.org/docs/getting_started/quick_start)
`curl -L noirup.dev | bash`

[Foundry](https://book.getfoundry.sh/getting-started/installation#using-foundryup)
`curl -L https://foundry.paradigm.xyz | bash`

## Other cool stuff

[Proving on the browser](https://github.com/AztecProtocol/noir-starter/tree/main/vite-hardhat)

[Recursive proofs... On the browser](https://github.com/noir-lang/noir-examples/tree/master/recursion)

## I trust you bro

Unless you want to, you don't need to run the tools inside "utils". Here are the hashes we're gonna need, for your copy-pasting pleasures:

Poseidon:

```toml
x = [1,2]
y = "0x115cc0f5e7d690413df64c6b9662e9cf2a3617f2743245519e19607a4417189a"
```

Keccak:

```toml
x = [1,2]
y = [
   34, 174, 109, 166, 180, 130, 249, 177,
  177, 155,  11, 137, 124,  63, 212,  56,
  132,  24,  10,  28,  94, 227,  97, 225,
   16, 122,  27, 198,  53, 100, 157, 218
]
```

Same for my favourite lib:

```toml
[dependencies]
ecrecover = {tag = "v0.30.0", git = "https://github.com/colinnielsen/ecrecover-noir.git"}
```

[^fn]: nope
