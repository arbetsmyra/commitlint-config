# [2.1.0](https://github.com/arbetsmyra/commitlint-config/compare/v2.0.0...v2.1.0) (2020-09-15)


### Bug Fixes

* **deps:** npm audit fix ([17ddffe](https://github.com/arbetsmyra/commitlint-config/commit/17ddffe34d382baf2234113f0b6b60d51682bb81))


### Features

* force new minor ([4055ff4](https://github.com/arbetsmyra/commitlint-config/commit/4055ff4cdd0f59bd0c9979b782a694e653415694))

# [2.0.0](https://github.com/arbetsmyra/commitlint-config/compare/v1.3.2...v2.0.0) (2020-08-10)


### Build System

* make @commitlint/cli peerDependency ([e1e5aaa](https://github.com/arbetsmyra/commitlint-config/commit/e1e5aaaf5a2caa6f521863dbc1412ca6e49ce932))


### BREAKING CHANGES

* previously the config was delivered with commitlint/cli as
a dependency but this is now changed to be a peer dependency. The consumer
now needs to install the package with: `npm install --save-dev @commitlint/cli`.

## [1.3.2](https://github.com/arbetsmyra/commitlint-config/compare/v1.3.1...v1.3.2) (2020-07-13)


### Bug Fixes

* **deps:** update commitlint monorepo to v9.1.1 ([8d75d1b](https://github.com/arbetsmyra/commitlint-config/commit/8d75d1bbd92e2ee77e462d87b5d5f427844d0590))

## [1.3.1](https://github.com/arbetsmyra/commitlint-config/compare/v1.3.0...v1.3.1) (2020-06-21)


### Bug Fixes

* **deps:** update commitlint monorepo to v9 ([1717c04](https://github.com/arbetsmyra/commitlint-config/commit/1717c04753a971a18afe8b9abe9890ef2c3c4204))

# [1.3.0](https://github.com/arbetsmyra/commitlint-config/compare/v1.2.0...v1.3.0) (2020-05-04)


### Features

* replace config-angular with config-conventional ([4f3c6fd](https://github.com/arbetsmyra/commitlint-config/commit/4f3c6fd4a1d5110b47a1088d9cf61c43130fd98f))

# [1.2.0](https://github.com/arbetsmyra/commitlint-config/compare/v1.1.0...v1.2.0) (2020-05-01)


### Features

* bundle commitlint with package (no peerDependencies) ([c6112a2](https://github.com/arbetsmyra/commitlint-config/commit/c6112a264325f8454b936611c168f9c7d789ea13))

# [1.1.0](https://github.com/arbetsmyra/commitlint-config/compare/v1.0.0...v1.1.0) (2020-05-01)


### Features

* use arbetsmyra semantic-release config ([f4851b1](https://github.com/arbetsmyra/commitlint-config/commit/f4851b15eb7529184c059127ea9c9f40d7049b6c))
