# hexpm-rust

A Rust client for [Hex][hex], the package manager for the Erlang ecosystem.

This library was created for use in the [Gleam programming language][gleam]
compiler, and as such only currently supports the endpoints used by Gleam.

[hex]: https://hex.pm/
[gleam]: https://gleam.run/

---

I've executed this command, taken from
https://briansmith.org/rustdoc/ring/signature/index.html#signing-and-verifying-with-rsa-pkcs1-15-padding :

```
openssl rsa -pubin \
            -in test/public_key \
            -inform PEM \
            -RSAPublicKey_out \
            -outform DER \
            -out test/public_key.der
```
