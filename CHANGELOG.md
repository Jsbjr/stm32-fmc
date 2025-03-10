# Changelog

## [Unreleased]

## [v0.2.2] 2021-03-27

* Implement AS4C16M32MSA-6BIN device #3

## [v0.2.1] 2020-11-07

* Export SdramConfiguration and SdramTiming structs to fix implementing
  SdramChip outside the crate https://github.com/stm32-rs/stm32-fmc/pull/2

## [v0.2.0] 2020-08-28

* *Breaking*: Use a generic type to support pin checking on SDRAMs with 11 and
  13 address lines. `PinsSdram` now has two generic types.

## [v0.1.2] 2020-08-05

* Don't require type to be `Sync` in order to implement FmcPeripheral
* Begin Changelog

[Unreleased]: https://github.com/stm32-rs/stm32-fmc/compare/v0.2.2...HEAD
[v0.2.1]: https://github.com/stm32-rs/stm32-fmc/compare/v0.2.1...v0.2.2
[v0.2.1]: https://github.com/stm32-rs/stm32-fmc/compare/v0.2.0...v0.2.1
[v0.2.0]: https://github.com/stm32-rs/stm32-fmc/compare/v0.1.2...v0.2.0
