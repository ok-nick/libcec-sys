# libcec-sys

[![Crates.io](https://img.shields.io/crates/v/libcec-sys.svg)](https://crates.io/crates/libcec-sys)
[![Docs.rs](https://docs.rs/libcec-sys/badge.svg)](https://docs.rs/libcec-sys)
[![CI](https://github.com/ssalonen/libcec-sys/workflows/Continuous%20Integration/badge.svg)](https://github.com/ssalonen/libcec-sys/actions)

FFI bindings for the libcec

## Installation

### Linking of libcec

By default, this crate tried to link to `libcec` version >= 4.0.0. `pkg-config` is always preferred when available.
Alternatively, one can use vendored sources by enabling `vendored` feature.

## License

Licensed under GNU General Public License version 2, ([LICENSE](LICENSE) or [https://opensource.org/licenses/GPL-2.0](https://opensource.org/licenses/GPL-2.0))

The CI/CD setup in `.github/` is based on [rust-github/template](https://github.com/rust-github/template), and therefore licensed under  either of

* Apache License, Version 2.0
   ([LICENSE-CI-APACHE](LICENSE-APACHE) or [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0))
* MIT license
   ([LICENSE-CI-MIT](LICENSE-MIT) or [http://opensource.org/licenses/MIT](http://opensource.org/licenses/MIT))

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.

See [CONTRIBUTING.md](CONTRIBUTING.md).

## Releasing

```cargo release --skip-publish``` and let the github CD pipeline do the rest.
