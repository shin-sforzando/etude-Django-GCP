# etude-Django-GCP

<!-- Badges -->
[![CI](https://github.com/shin-sforzando/etude-Django-GCP/actions/workflows/ci.yml/badge.svg)](https://github.com/shin-sforzando/etude-Django-GCP/actions/workflows/ci.yml)
[![Bump Version](https://github.com/shin-sforzando/etude-Django-GCP/actions/workflows/bump-version.yml/badge.svg)](https://github.com/shin-sforzando/etude-Django-GCP/actions/workflows/bump-version.yml)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

<!-- Screenshots -->
|![Screenshot 1](https://placehold.jp/32/3d4070/ffffff/720x480.png?text=Screenshot%201)|![Screenshot 2](https://placehold.jp/32/703d40/ffffff/720x480.png?text=Screenshot%202)|
|:---:|:---:|
|Screenshot 1|Screenshot 2|

<!-- Synopsis -->
**etude-Django-GCP** is Sample Repository for Mr. Yokoyama.

<!-- TOC -->
- [Prerequisites](#prerequisites)
- [How to](#how-to)
  - [Setup](#setup)
    - [Reveal Secrets](#reveal-secrets)
    - [Migrate Database](#migrate-database)
  - [Develop](#develop)
    - [Renew Containers](#renew-containers)
  - [Run](#run)
  - [Lint](#lint)
  - [Test](#test)
  - [Deploy](#deploy)
  - [Document](#document)
- [Misc](#misc)
- [Notes](#notes)
  - [LICENSE](#license)
  - [Contributors](#contributors)

## Prerequisites

- Docker (Version 20.10.8 or higher)
  - Python 3.9
    - Django 4.0

## How to

```shell
$ make help
ps                   監視
up                   起動
migrate              移行
setup                初回
restart              再起
renew                転生
shell                接続
logs                 記録
follow               追跡
open                 閲覧
hide                 秘匿
reveal               暴露
deploy               配備
stop                 停止
down                 削除
clean                掃除
prune                破滅
help                 助言
```

### Setup

#### Reveal Secrets

```shell
make reveal
```

#### Migrate Database

```shell
make migrate
```

### Develop

#### Renew Containers

```shell
make renew
```

### Run

```shell
make up && make open && make follow
```

### Lint

```shell
(T. B. D.)
```

### Test

```shell
(T. B. D.)
```

### Deploy

```shell
(T. B. D.)
```

### Document

```shell
(T. B. D.)
```

## Misc

## Notes

This repository is [Commitizen](https://commitizen.github.io/cz-cli/) friendly.

### LICENSE

See [LICENSE](LICENSE).

### Contributors

- [Shin'ichiro Suzuki](https://github.com/shin-sforzando)
