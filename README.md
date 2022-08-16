# w5100-rs

Embedded rust support for the [Wiznet W5100](https://www.wiznet.io/product-item/w5100/) SPI internet offload chip.

> **Warning**: This is still VERY much a work-in-progress. As in, it does not work, but I am making progress (:

* [`w5100-ll`] contains low-level drivers, register setters & getters.
* [`w5100-hl`] contains higher-level drivers.
* [`w5100-regsim`] contains a simulation of the [`w5100-ll`] `Registers` trait.
* Other crates contain protocol implementations.

[Wiznet W5100]: https://www.wiznet.io/product-item/w5100/
[`w5100-dhcp`]: https://github.com/mattrob33/w5100-rs/tree/main/dhcp
[`w5100-dns`]: https://github.com/mattrob33/w5100-rs/tree/main/dns
[`w5100-hl`]: https://github.com/mattrob33/w5100-rs/tree/main/hl
[`w5100-ll`]: https://github.com/mattrob33/w5100-rs/tree/main/ll
[`w5100-mqtt`]: https://github.com/mattrob33/w5100-rs/tree/main/mqtt
[`w5100-regsim`]: https://github.com/mattrob33/w5100-rs/tree/main/regsim
[`w5100-sntp`]: https://github.com/mattrob33/w5100-rs/tree/main/sntp
[`w5100-tls`]: https://github.com/mattrob33/w5100-rs/tree/main/tls
