# Changelog

This project follows semantic versioning.

Possible log types:

- `[added]` for new features.
- `[changed]` for changes in existing functionality.
- `[deprecated]` for once-stable features removed in upcoming releases.
- `[removed]` for deprecated features removed in this release.
- `[fixed]` for any bug fixes.
- `[security]` to invite users to upgrade in case of vulnerabilities.

### Unreleased

### v0.11.1 (2019-11-27)

- [fixed] Fix `uart` peripheral mappings for STM32L4/STM32L4+
- [fixed] Fix `dma`, `tim` peripheral mappings for STM32F4

### v0.11.0 (2019-11-06)

- [added] Add STM32F4 family support with `adc`, `dma`, `exti`, `gpio`, `tim`
  peripheral mappings
- [changed] Using `stm2_mcu` config flag to specify the MCU model
- [changed] Extracted `drone-svd` crate

### v0.10.1 (2019-09-27)

- [fixed] Fix API documentation by moving to self-hosted https://api.drone-os.com
