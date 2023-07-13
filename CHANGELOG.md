# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

### [2.0.1](https://github.com/creshpay/action-gpg/compare/v2.0.0...v2.0.1) (2023-07-13)


### Bug Fixes

* description too long ([5c742c4](https://github.com/creshpay/action-gpg/commit/5c742c49868f84a1b78754682e0d5e11a637d94b))

## [2.0.0](https://github.com/creshpay/action-gpg/compare/v1.0.3...v2.0.0) (2023-07-13)


### ⚠ BREAKING CHANGES

* use default `sh` shell instead of `bash`

### Features

* use default `sh` shell instead of `bash` ([d129a7a](https://github.com/creshpay/action-gpg/commit/d129a7aec93c065270b7467aacbec187881f65c7)), closes [#4](https://github.com/creshpay/action-gpg/issues/4)


### Bug Fixes

* handle spaces in git config values ([042947f](https://github.com/creshpay/action-gpg/commit/042947f9954d0e281f2bbe040699ce58a82d5a1c))
* improve GPG Agent configuration ([5aaeced](https://github.com/creshpay/action-gpg/commit/5aaecedfbc021386be9df551b3f5c1ce4a3e2531))


### Chore

* **ci:** update org name ref ([8b95e32](https://github.com/creshpay/action-gpg/commit/8b95e3272beed099dcede76faba0b653c5dad60b))
* improve title and description ([72cbfdb](https://github.com/creshpay/action-gpg/commit/72cbfdb3a7fe30d2776cf690d198ed2e2e1af7be))

### [1.0.3](https://github.com/cresh-io/action-gpg/compare/v1.0.2...v1.0.3) (2023-03-08)


### Chore

* **ci:** enable dependabot on ga ([#5](https://github.com/cresh-io/action-gpg/issues/5)) ([9c78379](https://github.com/cresh-io/action-gpg/commit/9c7837911f02a9351b72eea388bf576317fe23a3))
* configure standard-version changelog ([420d40a](https://github.com/cresh-io/action-gpg/commit/420d40a1b53967f2d97c4f7daadee6a55a95692d))
* **deps:** bump actions/checkout from 2 to 3 ([#6](https://github.com/cresh-io/action-gpg/issues/6)) ([beed0e3](https://github.com/cresh-io/action-gpg/commit/beed0e32752e09899f2585062a03112ea85c149b))

### [1.0.2](https://github.com/cresh-io/action-gpg/compare/v1.0.1...v1.0.2) (2022-07-12)


### Bug Fixes

* either use systemctl service either gpg-agent CLI ([#3](https://github.com/cresh-io/action-gpg/issues/3)) ([bb0379a](https://github.com/cresh-io/action-gpg/commit/bb0379a4ec361d1ec40d6568f193748cf9baf47e))

### [1.0.1](https://github.com/cresh-io/action-gpg/compare/v1.0.0...v1.0.1) (2022-07-12)


### Bug Fixes

* stop gpg-agent if already running ([#2](https://github.com/cresh-io/action-gpg/issues/2)) ([e2975ab](https://github.com/cresh-io/action-gpg/commit/e2975ab263bdb41c3ec5284f38778fec4e873eb1))

## 1.0.0 (2021-10-21)


### Features

* configure gpg agent and tell git to use it ([c5a5126](https://github.com/cresh-io/action-gpg/commit/c5a512635ed895507c1c7f833fda1fad8dab8b42))
