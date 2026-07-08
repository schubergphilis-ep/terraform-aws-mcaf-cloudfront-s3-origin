# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## [4.0.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v4.0.1...v4.0.2) (2026-07-07)


### 🐛 Fixes

* migrate MCAF module sources ([#2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/issues/2)) ([ac8916e](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/ac8916e5144b8da8486717ece22ff4528a4e06b2))

## [4.0.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v4.0.0...v4.0.1) (2026-06-18)


### 🐛 Fixes

* add kms:Decrypt permission for authentication lambda role … ([#149](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/149)) ([237a468](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/237a468d2d491372367d392ba94d56580f6e91da))

## [4.0.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v3.0.1...v4.0.0) (2026-06-18)


### ⚠ BREAKING CHANGES

* add existing Okta app support and permissions boundary passthr… ([#148](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/148))

### 🚀 Features

* add existing Okta app support and permissions boundary passthr… ([#148](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/148)) ([0481a50](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/0481a50225b8331b4c2702282aa3bb5c46b92742))

## [3.0.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v3.0.0...v3.0.1) (2026-06-17)


### 🐛 Fixes

* add optional permissions boundary for authentication lambda exec… ([#145](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/145)) ([20d9b47](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/20d9b47cdc551638b0b742eccfff1d7b48cff2a0))

## [3.0.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v2.1.2...v3.0.0) (2026-06-16)


### ⚠ BREAKING CHANGES

* `kms_key_arn` is now used to encrypt all relevant resources ([#144](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/144))
* `kms_key_arn` is now used to encrypt all relevant resources ([#144](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/144))

### 🐛 Fixes

* `kms_key_arn` is now used to encrypt all relevant resources ([#144](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/144)) ([c7d92ee](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/c7d92ee6a5545520ffb0287232c4ef9409a7b871))
* `kms_key_arn` is now used to encrypt all relevant resources ([#144](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/144)) ([c7d92ee](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/c7d92ee6a5545520ffb0287232c4ef9409a7b871))

## [2.1.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v2.1.1...v2.1.2) (2025-10-27)


### 🐛 Fixes

* Fix logging path ([#138](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/138)) ([908b274](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/908b274c65b1bee3d9f8abefaf67ee0522a0ae39))

## [2.1.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v2.1.0...v2.1.1) (2025-10-27)


### 🐛 Fixes

* Fix logging bucket arn ([#137](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/137)) ([2b89754](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/2b8975418f2ed1a84e9e2a35a2e2cbbb3f18881c))

## [2.1.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v2.0.0...v2.1.0) (2025-10-27)


### 🚀 Features

* Add access log configuration feature ([#136](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/136)) ([abeffdc](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/abeffdc419c9b2de8cacc9f600e220785f3600bf))

## [2.0.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v1.0.1...v2.0.0) (2025-09-30)


### ⚠ BREAKING CHANGES

* Add region support ([#129](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/129))

### 🚀 Features

* Add basic security headers settings ([#132](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/132)) ([059c767](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/059c767fba27ba2923def5dd476a015a5c544367))
* Migration from AOI to AOC ([#130](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/130)) ([f9a70ff](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/f9a70ffc9460b6bcd3c44404ac1f3db2d7ad33c3))
* Add region support ([#129](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/129)) ([41d81dc](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/41d81dc750c6fb2c88727a7dc6408e32018b0f26))

### 🐛 Fixes

* Bump axios from 0.30.0 to 1.12.0 in /auth_lambda ([#128](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/128)) ([88cd94a](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/88cd94a528b1214565ed1d1fe6ecaa6ec793b3ef))

## [1.0.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v1.0.0...v1.0.1) (2025-06-17)


### 🐛 Fixes

* Updated Lambda ([#127](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/127)) ([a483aae](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/a483aaefe87f81b68a7a0116826b81eab71879c9))
* Add mandatory "create_policy" attribute ([#126](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/126)) ([25b3606](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/25b3606d84d04758fc73c2005c20e717769d30f2))

## [1.0.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.12.0...v1.0.0) (2025-06-13)


### 🚀 Features

* Initial version of the new style MCAF development ([#125](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/125)) ([04bc0be](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/04bc0be75d44141a979319e644612d654d5d66ff))
* Bump axios from 0.21.4 to 0.30.0 in /auth_lambda ([#123](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/123)) ([160f382](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/160f382cde1eb591301e2e0b58e820b95d6bf903))
* Initial version of the new style MCAF development ([#125](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/125)) ([04bc0be](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/04bc0be75d44141a979319e644612d654d5d66ff))
* Initial version of the new style MCAF development ([#125](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/125)) ([04bc0be](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/04bc0be75d44141a979319e644612d654d5d66ff))
* Initial version of the new style MCAF development ([#125](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/pull/125)) ([04bc0be](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/commit/04bc0be75d44141a979319e644612d654d5d66ff))

## [0.12.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.15...v0.12.0) (2025-05-13)

## [0.11.15](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.14...v0.11.15) (2024-10-28)

## [0.11.14](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.13...v0.11.14) (2024-04-12)

## [0.11.13](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.11...v0.11.13) (2023-09-11)

## [0.11.11](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.12...v0.11.11) (2023-06-13)

## [0.11.12](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.10...v0.11.12) (2023-06-13)

## [0.11.10](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.9...v0.11.10) (2023-05-25)

## [0.11.9](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.8...v0.11.9) (2023-05-17)

## [0.11.8](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.7...v0.11.8) (2023-05-16)

## [0.11.7](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.6...v0.11.7) (2023-05-05)

## [0.11.6](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.5...v0.11.6) (2023-04-24)

## [0.11.5](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.4...v0.11.5) (2023-02-09)

## [0.11.4](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.3...v0.11.4) (2023-01-12)

## [0.11.3](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.2...v0.11.3) (2022-09-15)

## [0.11.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.1...v0.11.2) (2022-08-26)

## [0.11.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.11.0...v0.11.1) (2022-07-08)

## [0.11.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.10.0...v0.11.0) (2022-03-07)

## [0.10.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.9.2...v0.10.0) (2021-11-18)

## [0.9.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.9.1...v0.9.2) (2021-11-11)

## [0.9.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.8.2...v0.9.1) (2021-10-26)

## [0.8.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.9.0...v0.8.2) (2021-07-27)

## [0.9.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.8.1...v0.9.0) (2021-07-27)

## [0.8.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.8.0...v0.8.1) (2021-06-26)

## [0.8.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.7.10...v0.8.0) (2021-06-17)

## [0.7.10](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.7.9...v0.7.10) (2021-06-01)

## [0.7.9](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.6.7...v0.7.9) (2021-05-27)

## [0.6.7](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.7.8...v0.6.7) (2021-05-25)

## [0.7.8](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.7.7...v0.7.8) (2021-05-25)

## [0.7.7](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.7.6...v0.7.7) (2021-05-21)

## [0.7.6](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.7.0...v0.7.6) (2021-05-20)

## [0.7.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.7.1...v0.7.0) (2021-05-19)

## [0.7.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.7.2...v0.7.1) (2021-05-19)

## [0.7.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.7.3...v0.7.2) (2021-05-19)

## [0.7.3](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.7.4...v0.7.3) (2021-05-19)

## [0.7.4](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.7.5...v0.7.4) (2021-05-19)

## [0.7.5](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.6.5...v0.7.5) (2021-05-19)

## [0.6.5](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.6.6...v0.6.5) (2021-04-21)

## [0.6.6](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.6.3...v0.6.6) (2021-04-21)

## [0.6.3](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.6.4...v0.6.3) (2021-02-02)

## [0.6.4](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.6.2...v0.6.4) (2021-02-02)

## [0.6.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.6.1...v0.6.2) (2020-11-17)

## [0.6.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.6.0...v0.6.1) (2020-11-03)

## [0.6.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.5.0...v0.6.0) (2020-10-27)

## [0.5.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.4.2...v0.5.0) (2020-08-03)

## [0.4.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.4.1...v0.4.2) (2020-07-28)

## [0.4.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.4.0...v0.4.1) (2020-06-18)

## [0.4.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.3.2...v0.4.0) (2020-06-11)

## [0.3.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.3.1...v0.3.2) (2020-06-04)

## [0.3.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.3.0...v0.3.1) (2020-01-10)

## [0.3.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.2.9...v0.3.0) (2020-01-07)

## [0.2.9](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.2.8...v0.2.9) (2019-12-18)

## [0.2.8](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.2.6...v0.2.8) (2019-12-05)

## [0.2.6](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.2.7...v0.2.6) (2019-12-03)

## [0.2.7](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.2.5...v0.2.7) (2019-12-03)

## [0.2.5](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.2.4...v0.2.5) (2019-11-27)

## [0.2.4](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.2.3...v0.2.4) (2019-11-25)

## [0.2.3](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.2.2...v0.2.3) (2019-11-22)

## [0.2.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.2.1...v0.2.2) (2019-11-19)

## [0.2.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.2.0...v0.2.1) (2019-10-28)

## [0.2.0](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.1.11...v0.2.0) (2019-10-24)

## [0.1.11](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.1.10...v0.1.11) (2019-09-26)

## [0.1.10](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.1.8...v0.1.10) (2019-09-23)

## [0.1.8](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.1.9...v0.1.8) (2019-09-16)

## [0.1.9](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.1.7...v0.1.9) (2019-09-16)

## [0.1.7](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.1.6...v0.1.7) (2019-09-09)

## [0.1.6](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.1.5...v0.1.6) (2019-09-05)

## [0.1.5](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.1.4...v0.1.5) (2019-08-26)

## [0.1.4](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.1.2...v0.1.4) (2019-08-09)

## [0.1.2](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.1.3...v0.1.2) (2019-08-08)

## [0.1.3](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.1.1...v0.1.3) (2019-08-08)

## [0.1.1](https://github.com/schubergphilis-ep/terraform-aws-mcaf-cloudfront-s3-origin/compare/v0.1.0...v0.1.1) (2019-08-07)

## 0.1.0 (2019-08-06)
